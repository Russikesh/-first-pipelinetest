pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building RJ Pipeline...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Test') {
     steps {
        echo 'Testing RJ Pipeline...'
     }
   }
   stage('Deploy') {
     steps {
       echo 'Deploying RJ Pipeline...'
     }
   }
  }
}
