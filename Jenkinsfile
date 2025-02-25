pipeline
{
  agent any
  stages
  {
    stage('clone repository')
    {
      steps
    {
      git''
    }
  }
  stage
  {
    step('build')
    {
      sh 'javac Hello.java'
    }
  }
  stage
  {
    step('run')
    {
      sh 'java Hello'
    }
  }
}
}
