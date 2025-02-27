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
  stage('Build')
  {
    steps
    {
      sh 'javac hi.java'
    }
  }
  stage('Run')
  {
    steps
    {
      sh 'java hi'
    }
  }
}
}
