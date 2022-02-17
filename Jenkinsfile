pipeline{
  agent any
  
  stages {
  stage('maven install') {
    steps {
      withMaven(jdk: 'ec2jdk', maven: 'Maven3') {
    sh 'mvn clean install'
}
    }
  }

}

  
}
