#!/usr/bin/env groovy

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
                bash 'echo %CC%'
                bash 'echo %DEBUG_FLAGS'
            }
        }
    }
}