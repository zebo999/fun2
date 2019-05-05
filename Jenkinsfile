pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                echo 'Wow'
                sh 'pwd'
                sh 'yamllint test.yaml'
            }
        }
    }
}
