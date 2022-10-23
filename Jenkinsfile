pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello world'
            }
        }
        
        stage('BUILD') {
            steps {
                echo 'Developpement'
            }
        }
        stage('TEST') {
            steps {
                echo 'Testing'
            }
        }
        stage('DEPLOY') {
            steps {
                echo 'Mise en production'
            }
        }
    }
}
