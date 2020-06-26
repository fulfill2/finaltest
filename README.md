 # Info
```
⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯
 Instructor : 이지혜
  E-Mail     : fulfill2@gmail.com
 ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯

  ```

  # Usage
  * docker pull fulfill2/finaltest
  * docker images
  * docker run -it fulfill2/finaltest:latest

  ```
   $ docker build --tag fulfill2/finaltest .
   $ docker run -it fulfill2/finaltest:latest
     root@1a35d80d544f:/# 
  ```
# 사용결과
```
$ docker build --tag fulfill2/finaltest .                                                                                                                                                   Sending build context to Docker daemon  88.06kB                                                                                                                                             Step 1/4 : FROM ubuntu                                                                                                                                                                       ---> 74435f89ab78                                                                                                                                                                          Step 2/4 : RUN apt update                                                                                                                                                                    ---> Using cache                                                                                                                                                                            ---> f5332d79e51c                                                                                                                                                                          Step 3/4 : RUN apt install -y nginx                                                                                                                                                          ---> Using cache                                                                                                                                                                            ---> 2884120e7137                                                                                                                                                                          Step 4/4 : CMD ["nginx", "-g", "daemon off;"]                                                                                                                                                ---> Running in 38229b6158e7                                                                                                                                                               Removing intermediate container 38229b6158e7                                                                                                                                                 ---> 3b8e4582aae0                                                                                                                                                                          Successfully built 3b8e4582aae0                                                                                                                                                             Successfully tagged fulfill2/finaltest:latest                                                                                                                                               SECURITY WARNING: You are building a Docker image from Windows against a non-Windows Docker host. All files and directories added to build context will have '-rwxr-xr-x' permissions. It is recommended to double check and reset permissions for sensitive files and directories. 
```