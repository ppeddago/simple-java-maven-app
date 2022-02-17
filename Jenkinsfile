pipeline{
  agent any
  
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'ec2jdk', maven: 'Maven3', mavenSettingsConfig: 'null') {
    sh 'mvn clean install'
}
    }
  }

}

  
}
