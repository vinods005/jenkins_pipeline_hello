pipeline
{

  agent any
  {
   stage "SCM checkout"{
   git 'https://github.com/vinods005/jenkins_pipeline_hello.git'
    }
    
    withMaven(maven: 'Local Maven') {
    sh 'mvn test'
    }
   
  }

}
