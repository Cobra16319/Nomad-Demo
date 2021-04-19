# Nomad-Demo
Fun Demo to get up and running with Nomad

## This AMI can be used for learning; update if you want to use in production. It has a current version of Nomad and Packer at time of commit

## Pull in the module and it will create 42 resources and setup all the routes and security groups for 9 instances running on AWS with auto-scaling and Consul and Nomad already configured. 


```
$ git pull https://github.com/Cobra16319/Nomad-Demo.git
```

```
$ Terraform init
```
```
$ Terraform Plan 
```
```
$ Terraform Apply
```


## Ensure you grab the SSH Key From AWS and have fun! Check the ./terraform directory for the full use and viewing of the module used.
