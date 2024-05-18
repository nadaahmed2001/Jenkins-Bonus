pipeline {
    agent any

    stages {
        stage('Clone Jenkins-Bash-Pipeline') {
            steps {
                bat 'git clone https://github.com/nadaahmed2001/Jenkins-Bash-Pipeline.git'
            }
        }

        stage('Execute labTask5.bat from Jenkins-Bash-Pipeline') {
            steps {
                bat 'call Jenkins-Bash-Pipeline\\labTask5.bat'
            }
        }
    }
}
