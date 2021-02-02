Terraform
=========

```sh
$ echo $PATH
$ mv ~/Downloads/terraform /usr/local/bin/
$ terraform
$ terraform version     # Show the current Terraform version
```

```sh
$ export AWS_PROFILE=jonnyalexbh
$ terraform init        # Prepare your working directory for other commands
$ terraform validate    # Check whether the configuration is valid
$ terraform plan        # Show changes required by the current configuration
$ terraform apply       # Create or update infrastructure
$ terraform destroy     # Destroy previously-created infrastructure
```

## License

MIT
