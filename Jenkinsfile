pipeline {
    agent any 
    //{
      //  docker {
        //    image 'maven:3-alpine'
        //    args '-v /root/.m2:/root/.m2'
       // }
  //  }
    stages {
        stage('Build') {
            steps {
              //  sh 'mvn -B -DskipTests clean package'
              echo 'Building....'
            }
        }
        stage('Test') {
            steps {
               // sh 'mvn test'
                echo 'Testing....'
            }
           // post {
            //    always {
            //        junit 'target/surefire-reports/*.xml'
            //    }
           // }
        }
        stage('Deploy') {
            steps {
                //sh './jenkins/scripts/deliver.sh'
                 echo 'Deploying....'
            }
        }
    }
}
