pipeline {
    agent any

    stages { 
        stage ('Inicial') { 
            steps {
                script {
                    dockerapp = docker.build( "hefi1413/java-hello:${env.BUILD_ID}", '-f ./Dockerfile .')
                }
            }
        }
    }
}