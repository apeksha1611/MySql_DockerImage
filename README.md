# MySql_DockerImage

    1.) Create a Dockerfile and test.sql file
    2.) Add the code as required in them.
    3.) Then in the terminal give the following commands

        docker build . -t mytestsql:0.1
        docker run -itd mytestsql:0.1
        docker exec -it <your container id which you can get by giving command docker ps> bash
        mysql -upucsd -p
        use pucsdStudents
        select * from studentData
