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
                // Ejemplo de comando (dependiendo del lenguaje):
                // sh 'mvn clean install'   // Java con Maven
                // sh 'npm install'         // Node.js
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
                // sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Desplegando aplicación...'
                // Aquí pondrías comandos de despliegue
            }
        }
    }
}
