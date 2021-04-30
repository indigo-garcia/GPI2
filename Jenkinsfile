pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                make /home/alumno/Escritorio/GPI2/ejercicio_3_practica_build_1/MyArduinoProject/src/FooProject/Makefile
            }
        }
    }
}
