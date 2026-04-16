pipeline {
    agent any

    stages { 
        stage ('Inicial') { 
            steps {
                scripts {
                    dockerapp = docker.build( "hefi1413/java-hello", '-f ./Dockerfile .')
                }
                echo 'Iniciando a pipeline'
            }
        }
    }
}