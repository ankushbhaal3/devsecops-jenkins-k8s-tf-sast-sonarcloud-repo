pipeline {
  agent any
  tools { 
        maven 'Maven_3_5_2'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=asgbuggywebapp7 -Dsonar.organization=asgbuggywebapp7 -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=07c6eaf77518742728675adb6002a9be744fec98
}
