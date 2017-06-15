# flight-school
learn to fly

## Reporting Issues and Requesting Features

Please report all issues and feature requests in [concourse/concourse](https://github.com/concourse/concourse/issues).

fly -t lite login -c http://192.168.100.4:8080/                
fly -t lite set-pipeline -p flight-school -c ci/pipeline.yml       
fly -t lite unpause-pipeline -p flight-school 
