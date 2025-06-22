pipeline {
    agent any

    stages {
        stage('Clonar Repositório') {
            steps {
                echo 'Clonando código...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Construindo aplicação...'
                sh 'echo "Build ok!"'
            }
        }

        stage('Testes') {
            steps {
                echo 'Executando testes fictícios...'
                sh 'echo "Testes passaram!"'
            }
        }

        stage('Final') {
            steps {
                echo 'Pipeline finalizado com sucesso.'
            }
        }
    }
}
