## Create a use with no permissions

```sh 
aws iam create-user --user-name sts-machine-user

aws iam  create-access-key --user-name sts-machine-user --output table

```

## Create a role

## Use new user credentials and assume role 
