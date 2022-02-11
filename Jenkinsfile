node{
  stage("SCM Checkout"){
    git "https://github.com/battanaveenkumar/mavenproject"
   }
    stage ("compile-package"){
      bat "mvn package"
    }
  }
