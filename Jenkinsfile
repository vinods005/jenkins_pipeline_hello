pipeline
{
  agent any
    
  stages 
  {
    stages ('SCM checkout') {
    git 'https://github.com/vinods005/jenkins_pipeline_hello.git'
    }
	
	stages ('Testing Stage') {
	
	
	steps{
    withMaven(maven: 'Local Maven') {
    sh 'mvn test'
    }
        }
  }
 }
}
