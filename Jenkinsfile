node{
   stage('SCM checkout'){
     git 'https://github.com/Sandeep0045/maven-app.git'
   }
   
   
  stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
  }
}
