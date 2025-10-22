### Terraform Notes 
  - first made an alias in .zshrc so tf is Terraform
  - wrote a sample in ./learn-terraform-docker-container/main.tf based on website tutorial
    - this creates a docker container by first creating an image from the TF registry, for Nginx. Then, it maps 80 on container to 8000 on localhost, then visiting the page brought me to the nginx container homepage. 
  - **tf** plan to see what Terraform will do
  - **tf** validate and fmt to make sure config is valid for Terraform
  - **tf** apply and typing "yes" will create the infrastructure
  - **docker ps** shows the container running once terraform is done 
  - the container will only run one at a time, and if you rerun the plan it destroys the old container
