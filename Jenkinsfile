def gv

pipeline {
    agent any
    
    stages {
        stage("build") {
            steps {
                echo 'building the application'
                
                script {
                    def test = 2 + 2 > 3 ? 'right' : 'wrong'
                    echo test
                }
            }
        }
        stage("test") {
            steps {
                script {
                    echo 'testing the application'
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo 'deploying the application'
                }
            }
        }
    }   
}
