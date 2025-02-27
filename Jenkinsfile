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
  stage('build')
  {
    steps
    {
      sh 'javac Hello.java'
    }
  }
  stage('Run')
  {
    steps
    {
      sh 'java Hello'
    }
  }
}
}
