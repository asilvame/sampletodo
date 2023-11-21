pipeline {
    agent any
    
    stages{
        stage ("Build Image"){
            steps {
                script {
                    dockerapp = docker.build("mesquita/sampletodoaula3:v${env.BUILD_ID}", '-f ./dockerfile .')
                }
            }
        }

    }
}
