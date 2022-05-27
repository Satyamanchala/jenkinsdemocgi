pipeline {
    agent any

    stages {
        stage('file1') {
            steps {
                git 'https://github.com/Satyamanchala/jenkinsdemocgi.git'
                bat "./mybatch.bat"
            }
        }
         stage('file2') {
            steps {
                git 'https://github.com/Satyamanchala/jenkinsdemocgi.git'
                bat "./mybatch2.bat"
            }
        }
       
    }
}
