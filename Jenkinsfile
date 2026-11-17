pipeline {
    agent any

    stages {
        stage('Vérification Git') {
            steps {
                echo 'Code récupéré depuis GitHub avec succès !'
                sh 'ls -la'
            }
        }
        stage('Build') {
            steps {
                echo 'Compilation en cours...'
            }
        }
        stage('Test') {
            steps {
                echo 'Exécution des tests...'
            }
        }
    }
}
