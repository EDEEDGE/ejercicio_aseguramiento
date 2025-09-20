pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Clonando el repositorio...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Compilando el proyecto...'
                
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
                
            }
        }

        stage('Deploy') {
            steps {
                echo 'Desplegando aplicación...'
                
            }
        }
    }
}
