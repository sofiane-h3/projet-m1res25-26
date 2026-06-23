pipeline {
    agent any

    stages {
        stage('Clean workspace') {
            steps {
                sh 'rm -r projet-m1res25-26'
            }
        }
        stage('Checkout SCM') {
            steps {
                sh 'git clone https://github.com/sofiane-h3/projet-m1res25-26.git'
            }
        }
    }
}
