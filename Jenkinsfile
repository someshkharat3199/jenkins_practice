pipeline{
    agent any
    environment{
        CC = 'clang'
        env.PATH = env.PATH + ";C:\\Windows\\System32"
    }
    stages{
        stage('Example'){
            environment{
                DEBUG_FLAGS = '-g'
            }
            steps{
                bat 'dir'
            }
        }
    }
}