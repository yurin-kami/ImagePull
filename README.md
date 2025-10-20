## ImagePull

a bash script to pull docker image(ocr fomat)

### Usage

- preconditions
  you must fork and clone the other repo in path/to/ImagePull/FORK_CLONE_REPO.
  The repo url is https://github.com/yurin-kami/docker_image_pusher
  you should config your git because this script will use git push renew the FORK_CLONE_REPO to add image

- bashenv:

```bash
export aliyun_registry=""#*.cn-hangzhou.personal.cr.aliyuncs.com
export aliyun_namespace=""#your aliyun container image service instance name
export aliyun_username=""#your aliyun container image service username
export aliyun_password=""#your aliyun container image service password
```

- command:

```bash
chmod +x image_pull
image_pull --help
image_pull -c [docker,ctr,nerdctl,podman] -i image_name:tag
image_pull [docker.io/k8s.io/other]/namespace/image_name:tag
```
