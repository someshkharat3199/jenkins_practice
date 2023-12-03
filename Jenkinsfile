pipeline{
    agent any
    environment{
        CC = 'clang'
        PATH = 'C:\\Windows\\System32'
    }
    stages{
        stage('Example'){
            environment{
                DEBUG_FLAGS = '-g'
            }
            steps{
                bat 'dir'
                echo '${PATH}'
                echo '${CC}'
            }
        }
    }
}