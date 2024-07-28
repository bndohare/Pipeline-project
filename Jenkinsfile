pipeline {
    agent any
    stages{
        stage("Build"){ 
            steps() {
              sh 'javac Testpipe.java'   
            }
           
        }
        stage("run"){
            steps(){
                  sh 'java Testpipe'
            }
          
        }
    }
    // post{
    //     always{
    //             sh 'good work'
    //     }
        
    // }
}