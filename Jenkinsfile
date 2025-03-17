pipeline 
{ 
agent any 
<<<<<<< HEAD
 stages { 
  /*
=======
 stages {
/* 
>>>>>>> 3cc058b (made changes to JenkinsFile)
  stage ('SCM checkout')
       {
     steps {
      sh 'git clone https://github.com/saurabhgore-code/HelloWorldMaven.git'
  }
    }
<<<<<<< HEAD
    */
=======
*/
>>>>>>> 3cc058b (made changes to JenkinsFile)
   stage('run maven project')
   { 
       steps {
           sh 'mvn clean install'
        }
}
/*
stage('send email notification') {
            steps {
                mail body: 'Build Failure', subject: 'Build Failure mail', to: 'saurabhgore65@gmail.com'
            }
        }
*/
    }
}

   
