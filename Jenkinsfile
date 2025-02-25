pipeline
{
  agent any
  stages
  {
    stage('clone repository')
    {
      steps
    {
      git 'https://github.com/rupa-555/demo1.git'
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
