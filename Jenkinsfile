node{
  stage("SCM Checkout"){
    git "https://github.com/battanaveenkumar/mavenproject/new/master"
   }
    stage ("compile-package"){
      .bat "mvn package"
    }
  }
