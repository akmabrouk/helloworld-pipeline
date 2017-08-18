pipeline {
  agent any
  triggers {
        // Run every 5 minutes
        cron('*/5 * * * *')
  }  
 stages {
        stage('Example') {
            steps {
                echo 'Hello Cron World'
            }
        }
    }  
}
