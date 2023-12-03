pipeline{
    agent any
    environment{
        CC = 'clang'
    }
    stages{
        stage('Example'){
            environment{
                DEBUG_FLAGS = '-g'
            }
            steps{
                bat 'dir'
                echo "${PATH}"
            }
        }
    }
}