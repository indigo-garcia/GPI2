pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                make /GPI2/ejercicio_3_practica_build_1/MyArduinoProject/src/FooProject/Makefile
                mvn test-compile /GPI2/ejercicio_4_practica_build_2/example-app/
                gradlew /GPI2/ejercicio_3_practica_build_1/Prueba/
            }
        }
    }
}
