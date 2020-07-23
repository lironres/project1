pipeline {
    agent any 
    stages {
        stage('clone') {
            steps {
                echo "clone repo"
                powershell("git clone https://github.com/lironres/project1.git")
            }
        }
            stage('Copy to Desktop') {
            steps {
                echo "Reading File Content"
                powershell("Move-Item myap.py \$home\desktop")
                
            }
        }
            
    }
}