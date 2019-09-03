node{
 stage("git checkout"){
  git credentialsId: 'webservergithubapikey', url: 'https://github.com/nourinb/javaparser-maven-sample'
  }
  stage("compile"){
  sh 'mvn package'
  }
 stage("slack notification"){
  slackSend baseUrl: 'https://hooks.slack.com/services/', channel: 'jenkins-demo-pipeline', color: 'good', message: 'Hi ,this message from jenkins pipeline', tokenCredentialId: 'slackdemo
 }
 
}
