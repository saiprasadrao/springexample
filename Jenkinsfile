pipeline{
  agent {
    label 'ec2-slave1'
  }
  stages{
    stage('Compile Source Code'){
      steps{
        echo 'Compiling Code using jenkinsfile'
        sh 'mvn compile'
      }
    }
  }
}
