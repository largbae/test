pipeline {
  agent any

  options { 
    disableConcurrentBuilds() 
  }

  parameters {
    choice(choices: 'DevEnv1\nDevEnv2', description: 'Which Database Slot?', name: 'envslot')
  }

  stages {
    stage('Validate Environment') {
      steps {
        echo "test: ${params.envslot}"
      }
    stage('Provision AIX Server') {
      steps {
        echo "test: ${params.envslot}"
      }
    stage('Prepare Oracle Software') {
      steps {
        echo "test: ${params.envslot}"
      }
    stage('Connect Delphix Datasource') {
      steps {
        echo "test: ${params.envslot}"
      }
    }
    stage('Deploy Application Layer') {
      steps {
        echo "test: ${params.envslot}"
      }
    stage('Run Tests') {
      steps {
        echo "test: ${params.envslot}"
      }
    }
  }
}
