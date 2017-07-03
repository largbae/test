pipeline {
  properties([parameters([string(defaultValue: 'xyz', description: 'string param', name: 'param1')]), pipelineTriggers([])])

  stages {
    stage('Test') {
      steps {
        echo 'test'
      }
    }
  }
}
