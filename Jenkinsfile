node{
   stage('SCM checkout'){
     git 'https://github.com/Sandeep0045/maven-app.git'
   }
   
   stage('compile package')
      sh "mvn -B -DskipTests clean package"
   }

}
