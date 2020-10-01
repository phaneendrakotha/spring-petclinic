pipeline {
     environment {

    sonarCredential = 'sonar-phkotha'
    shortCommit = sh(returnStdout: true, script: "git log -n 1 --pretty=format:'%h'").trim()

  }
  		
agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn -DskipTests clean install'
            }
        }
         
 

      

		
     
 
	}   
}
