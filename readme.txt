# These file will be first pushed on Git
# After that Jenkins will pull the file(and this is already configured by enabling githook in Jenkins )
# Jenkins will pull the file from Git, and it will be built as per script defined in Jenkins(or in JenkinsFile).
# Jenkinsfile is installing Docker on Remote Server and then docker will built the image as per the Dockerfile 
# Finally as defined in Jenkins Script , the container will be started by Docker on defined port.
# This will finally release the webpage on nginx server.     
  
# This is release attempt no 3