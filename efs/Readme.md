## Setting up

Install EFS utils in EC2

```sh
sudo yum install -y amazon-efs-utils
```


## Mounting EFS

```sh
sudo mount -t efs -o tls fs-0b24bd946ee1bebca:/ efs
```

