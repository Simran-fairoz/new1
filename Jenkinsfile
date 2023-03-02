pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
      stage('Test') {
            steps {
                echo 'Hello1 World'
            }
        }
      stage('Deploy') {
            steps {
                echo 'Hello2 World'
            }
        }
    }
    post{
        always{
            emailext body: 'saafaf', subject: 'hiasda', to: 'simranofficial55@gmail.com'
        }
    }
}
