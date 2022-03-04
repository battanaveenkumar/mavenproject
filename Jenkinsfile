node{
  stage("SCM Checkout"){
    git "https://github.com/battanaveenkumar/mavenproject"
   }
    stage ("verify"){
      bat "mvn verify"
    }
  }
