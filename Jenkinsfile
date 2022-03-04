node{
  stage("SCM Checkout"){
    git "https://github.com/battanaveenkumar/mavenproject"
   }
    stage ("compile-test"){
      bat "mvn test"
    }
  }
