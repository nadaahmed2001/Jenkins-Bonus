pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                script {
                    if (fileExists('Jenkins-Bash-Pipeline')) {
                        bat 'rm -rf Jenkins-Bash-Pipeline'
                    }
                    
                    git 'https://github.com/nadaahmed2001/Jenkins-Bash-Pipeline.git'
                }
            }
        }

        stage('Execute Script') {
            steps {
                script {
                    dir('Jenkins-Bash-Pipeline') {
                        bat 'labTask5.bat'
                    }
                }
            }
        }
    }
}
