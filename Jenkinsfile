node{
 stage("git checkout"){
  git credentialsId: 'webservergithubapikey', url: 'https://github.com/nourinb/javaparser-maven-sample'
  }
  stage("compile"){
  sh 'mvn package'
  }
}
