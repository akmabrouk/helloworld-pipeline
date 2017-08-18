pipeline {
  agent any
  triggers {
        // Run every minute
        cron('* * * * *')
  }  
 stages {
        stage('Example') {
            steps {
                echo 'Hello Cron World'
            }
        }
    }  
}
