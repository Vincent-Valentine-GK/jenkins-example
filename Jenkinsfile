pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                sh 'pwd'
                }

        }

        stage ('Testing Stage') {

            steps {
                sh 'echo "This is a test."'

            }
        }


        stage ('Deployment Stage') {
            steps {
                sh 'cat /etc/os-release'
            }
        }
    }
}