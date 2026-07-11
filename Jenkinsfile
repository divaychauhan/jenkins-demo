pipeline {
    agent { label 'electronix' }

    stages {
        stage('Hello') {
            steps {
                echo "Hello jenkins"
            }
        }

        stage('HELLO SECOND') {
            steps {
                echo "hello jenkins again"
            }
        }

        stage('MY NAME') {
            steps {
                echo "MY NAME IS DIVAY PRATAP SINGH CHAUHAN"
            }
        }
    }

    post {
        success {
            echo "Pipeline Passed ✅"
        }

        failure {
            echo "Pipeline Failed ❌"
        }
    }
}
