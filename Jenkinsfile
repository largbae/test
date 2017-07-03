pipeline {
  agent any

  options { 
    disableConcurrentBuilds() 
  }

  parameters {
    choice(choices: 'US-EAST-1\nUS-WEST-2', description: 'What AWS region?', name: 'region')
  }

  stages {
    stage('Test') {
      steps {
        echo "test: ${params.region}"
      }
    }
  }
}
