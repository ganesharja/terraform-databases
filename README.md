# terraform-databases
  This is the root module where we are going to call the backend module. Here is where we are going to execute the terraform commands.

All the *.tfvars or the files of tfvars with respect to environments will be supplied here.

Backend modules of this root module is tf-module-docdb , tf-module-redis , tf-module-mysql , tf-module-rabbitmq. Here is where we will build our code and will be used from different places.
