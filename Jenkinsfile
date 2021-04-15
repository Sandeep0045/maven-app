node{
   stage('SCM checkout'){
     git 'https://github.com/Sandeep0045/maven-app.git'
   }
   
   stage('compile package'){
      def mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvnHOME}/bin/mvn package"
   }

}
