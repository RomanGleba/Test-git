pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git url: 'git@github.com:RomanGleba/Pro-Deve.git',
                    credentialsId: 'Jenkins-git-key' // Використовуйте цей ID
            }
        }
        stage('Build') {
            steps {
                echo 'Збірка проекту...'
                sh 'echo "Hello, Jenkins!"'
            }
        }
    }
}
