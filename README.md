# docker-compose 
# run the docker-compose.yml follow the steps

The image used in the docker-compose.yml file is mysql basic image

    1. go to the directory where your docker-compose.yml is present.

    2. enter the command "sudo docker-compose up"

    It will run the mysql server wait till all the container starts.

    3.open another terminal and see which containers are running using "sudo docker ps" command.

    4.now execute the container to see whether container data that we gave is perfectly fetched into that container or not for that use bellow command

     "sudo docker exec -it "container_id" bash"

      NOTE: here in this command "container_id" represents your container id that we see in step 3. you can also give container name insteead of container_id.

    5.after firing the above command you get into mysql database and in this case we run the following command

     "mysql -uroot -ppucsd"

    NOTE: Here root is our username and pucsd is a password for the root both the things are defined in in docker-compose.yml file

Now you can see and make operations inside the container using mysql commands.

Thank You
