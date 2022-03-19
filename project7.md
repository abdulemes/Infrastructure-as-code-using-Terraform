## Project Workflow

Step 1 - Open VS code terminal and generate key for log in to our EC2 instance.

  Command: ssh keygen
  
  ![IMG_9319 2](https://user-images.githubusercontent.com/93732510/157644464-cdd7ae1b-ac13-4ac0-9230-2d68691a9dfb.jpg)

Step 2 - Create a variables.tf file to define variables.

![IMG_9320](https://user-images.githubusercontent.com/93732510/157644935-cf222afe-2abe-43af-b0e5-be790b032520.jpg)

Step 3 - Create a provider.tf file to define the cloud provider.

![IMG_9323](https://user-images.githubusercontent.com/93732510/157645338-ab47e797-e746-4236-ac63-1a6b7f3718bf.jpg)

Step 4 - Open a new folder in the same directory to write the bash script that will provision the resource. 

![IMG_9322](https://user-images.githubusercontent.com/93732510/157645723-8c782be0-7209-4c46-9510-48662ccd08e0.jpg)

Step 5 - Create the EC2 instance file to define the resources.

![IMG_9324](https://user-images.githubusercontent.com/93732510/157646379-f30f2727-8a84-4a77-a4c2-5f482e394f5b.jpg)

Side note - You can write the provisoner block in the same instance file.

Step 6 - Run terraform init.

Step 7 - Run terraform fmt to formart the files.

Step 8 - Run terraform validate to validate the code.

Step 9 - Run terraform plan to see changes that terraform will create.

Step 10 - Run terraform apply to apply changes

Stepp 11 - Check website via browser to using the public IP address.

![IMG_9328](https://user-images.githubusercontent.com/93732510/157648032-279a23c8-37e8-4e94-8b14-f14c7d121a52.jpg)

