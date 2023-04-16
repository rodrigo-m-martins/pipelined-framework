pipeline {
    agent any

    stages {
        stage('Stage #01 - Build Image') {
            steps {
                script {
                    dockerapp = docker.build("jenkins/pipelined-framework", '-f ./src/main/resources/container/DockerFile ./src/main/resources/container')
                }
            // echo 'Iniciando Stage01 no pipeline'
            }
        }
    }
}
