pipeline {
    agent any

    stages {
        stage('Run_Click') {
            steps {
                bat 'python click.py'
            }
        }
        stage('Run_Welcome') {
            steps {
                bat 'python welcome.py'
            }
        }
    }
}
