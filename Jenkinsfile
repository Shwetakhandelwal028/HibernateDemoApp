node{
  stage('SCM Checkout'){
     git 'https://github.com/Shwetakhandelwal028/HibernateDemoApp.git'
  }
   stage('Compile-Package'){
   def mvnHome = tool type: 'maven'
   sh "${mvnHome}/bin/mvn package"
   }


}
