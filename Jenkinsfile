node{
 stage("git checkout"){
  git 'https://github.com/nourinb/javaparser-maven-sample/new/master'
  }
  stage("compile"){
  sh 'mvn package'
  }
}
