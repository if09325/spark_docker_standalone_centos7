# spark_docker_standalone_centos7
Mount a Spark Cluster "StandAlone" on Docker using VirtualBox and Centos7

# spark_docker
Run Spark on Docker v.1.0

# Instructions :
After downloading the zip file :

execute the build.sh file to build the image ==> "bash build.sh"

or enter this command line ==> "docker build -t teamhadoop/bigdata ."

after building the image manage the containers as a set of inter-connected services with docker-compose : "docker-compose up"



# Run spark-shell or others(bash, pyspark ...etc.)

enter the following command line ==> "docker exec -it <master_name/master_id> spark-shell(or pyspark or ...)"

to get the master name or id : run ==> "docker-compose ps"
