node {

 stage('SCM checkout'){
  git 'https://github.com/sairameshreddypv/JunitMavenRepo'
 }
 stage('compile-package'){
  
  // get Maven Home path
  def mvnHome = tool name: 'maven-3', type: 'maven'
   sh 'mvn package'
 }
 

}
