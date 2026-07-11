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
            mail to : "divaypratap5113@gmail.com"
            subject : "SUCCESS"
            body : "EMAIL WORKING"
        }

        failure {
            echo "Pipeline Failed ❌"
        }
    }
}
