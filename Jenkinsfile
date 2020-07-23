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
                echo "Reading File Content"
                powershell("""Move-Item myapp.py C:\\Users\\Liron\\Desktop\\""")
                
            }
        }
            
    }
}