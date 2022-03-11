pipeline {
    agent any

    stages {
        stage('Test WS') {
            steps {ll
                sh "newman run Ejercicio2PabloMorales.postman_collection.json"
            }
        }
    }
}
