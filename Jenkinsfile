#!groovy
pipeline {
    agent any 
    stages {
        stage('clone') {
            steps {
                echo "clone repo"
                cmd("git clone https://github.com/lironres/project1.git")
            }
        }
            stage('Copy to Desktop') {
            steps {
                echo "move file"
                powershell("""Move-Item myapp.py C:\\Users\\Liron\\Desktop\\""")
                
            }
        }
            
    }
}