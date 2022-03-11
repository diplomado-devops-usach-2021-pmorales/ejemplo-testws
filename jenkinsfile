pipeline {
    agent any

    stages {
        stage('Test WS') {
            steps {
                sh "newman run Ejercicio2PabloMorales.postman_collection.json"
            }
        }
    }
}
