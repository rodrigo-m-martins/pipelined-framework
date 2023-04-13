pipeline{
    agent any

    stages{
        stage('Stage #01 - Build Image'){
            steps{
                script{
                    dockerapp = docker.build("projectFolder/projectName", '-f ./path-to/DockerFile ./src')
                }
                // echo 'Iniciando Stage01 no pipeline'
            }
        }
        stage('Stage 02 Draft'){
            steps{
                echo 'Iniciando Stage02 no pipeline'
            }
        }
        stage('Stage 03 Draft'){
            steps{
                echo 'Iniciando Stage03 no pipeline'
            }
        }
        stage('Stage 04 Draft'){
            steps{
                echo 'Iniciando Stage04 no pipeline'
            }
        }
        stage('Stage 05 Draft'){
            steps{
                echo 'Iniciando Stage05 no pipeline'
            }
        }
    }
    stage('Stage 06 Draft'){
            steps{
                echo 'Iniciando Stage06 no pipeline'
            }
        }
}