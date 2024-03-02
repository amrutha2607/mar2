pipeline {
    agent any

    stages {
        stage ('Git') {
            steps {
               git 'https://github.com/amrutha2607/mar2.git'
            }
        }
            stage ('run') {
                steps {
                    sh 'java Demo.java'
                   
                }
            }
        }
    }
