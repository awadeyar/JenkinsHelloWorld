pipeline{
agent any 
stages{
stage("Cleaning stage"){
      steps{
        echo "Hello world cleaning"
      }
    }
    stage("Build stage"){
      steps{
       javac HelloWorld.java
      }
    }
     stage("Run stage"){
      steps{
      java HelloWorld.java
      }
    }
}

}
