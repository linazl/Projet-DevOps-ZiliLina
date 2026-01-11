pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/linazl/Projet-DevOps-ZiliLina.git'
            }
        }

        stage('Build') {
            steps {
                dir('hello-devops') {
                    sh 'mvn clean package'
                }
            }
        }

        stage('Archive') {
            steps {
                archiveArtifacts artifacts: 'hello-devops/target/*.jar', allowEmptyArchive: true
            }
        }

        stage('Deploy') {
            steps {
                echo "Déploiement local ou cloud (optionnel)"
            }
        }
    }

    post {
        success {
            echo "Build et deploy réussis!"
        }
        failure {
            echo "Il y a eu une erreur dans le pipeline"
        }
    }
}
