
# [<img src=".bluebeluga.png" height="100" width="200" style="border-radius: 50%;" alt="@fancyremarker" />](https://github.com/blue-beluga/docker-terraform) bluebeluga/terraform

Alpine Linux image with [Terraform](https://www.terraform.io/) and [Amazon Web Services Command Line Interface](http://aws.amazon.com/cli/).

## What is terraform

Terraform provides a common configuration to launch infrastructure — from physical and virtual servers to email and DNS providers. Once launched, Terraform safely and efficiently changes infrastructure as the configuration is evolved.

Simple file based configuration gives you a single view of your entire infrastructure.

## How to use this image

```
docker run bluebeluga/terraform [--version] [--help] <command> [<args>]

```

## Using

### terraform apply

```
docker run --rm -v /data:/data bluebeluga/terraform apply [options]
```

### terraform destroy

```
docker run --rm -v /data:/data bluebeluga/terraform destroy [options] [DIR]
```

### terraform get

```
docker run --rm -v /data:/data bluebeluga/terraform get [options] PATH
```

### terraform graph

```
docker run --rm -v /data:/data bluebeluga/terraform graph [options]
```

### terraform init

```
docker run --rm -v /data:/data bluebeluga/terraform init [options] SOURCE [PATH]
```

### terraform output

```
docker run --rm -v /data:/data bluebeluga/terraform output [options] NAME
```

### terraform plan

```
docker run --rm -v /data:/data bluebeluga/terraform plan [options]
```

### terraform push

```
docker run --rm -v /data:/data bluebeluga/terraform push [options]
```

### terraform refresh

```
docker run --rm -v /data:/data bluebeluga/terraform refresh [options]
```

### terraform remote

```
docker run --rm -v /data:/data bluebeluga/terraform remote [options]
```

### terraform show

```
docker run --rm -v /data:/data bluebeluga/terraform show terraform.tfstate [options]
```

### terraform taint

```
docker run --rm -v /data:/data bluebeluga/terraform taint [options] name
```

### terraform version

```
docker run --rm bluebeluga/terraform version
```
