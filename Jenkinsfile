pipeline {
    agent any
    stages {
        stage('Source') {
            steps { echo 'Código descargado desde GitHub' }
        }
        stage('Build') {
            steps { echo 'Compilando proyecto...' }
        }
        stage('Test') {
            steps { echo 'Ejecutando pruebas...' }
        }
        stage('Deploy') {
            steps { echo 'Desplegando aplicación...' }
        }
    }
}
