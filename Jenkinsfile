node{
   stage('SCM Checkout'){
     echo "test panharith"
     git 'https://github.com/panharithyi/javahometech.git'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
}
