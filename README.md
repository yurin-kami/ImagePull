## ImagePull

a bash script to pull docker image(ocr fomat)

### Usage

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
image_pull image_name:tag
```
