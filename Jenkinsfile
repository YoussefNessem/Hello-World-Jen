pipeline {
    agent any

    stages {

        stage('Run Script') {
            steps {
                chmod +x script.sh
                sh './script.sh'
            }
        }

    }
}
