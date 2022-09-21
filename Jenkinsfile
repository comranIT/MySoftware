pipeline {
    agent any

    stages {
        stage('Run_Click') {
            steps {
                bat 'python new_button.py'
            }
        }
        stage('Run_Welcome') {
            steps {
                bat 'python new_screen.py'
            }
        }
    }
}
