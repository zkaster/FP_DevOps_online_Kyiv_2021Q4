pipeline {
  agent any
  stages {
    stage('Echo') {
      steps {
        echo 'Hello TEST'
      }
    }

    stage('Notification') {
      steps {
        mail(subject: 'TEST', body: 'TEST Jenkins', from: 'zkasterwork@gmail.com', to: 'zkaster@gmail.com')
      }
    }

  }
}