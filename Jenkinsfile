pipeline {
    agent any
    
    stages {
        stage("Docker Build") { 
            steps {
                echo "Building the docker image"
            }
        }
        stage("Docker Deploy") {
            steps {
                echo "Deploying the docker image"
            }
        }
        stage("Testing the Docker Image") {
            steps {
                echo "Testing the SDFCLI"
            }
        }
    }
}