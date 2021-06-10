pipeline {
  agent {
    node {
      label 'principal'
    }

  }
  stages {
    stage('Stage 1 - Bulid') {
      steps {
        echo 'Fase 1 de Stage Build'
      }
    }

    stage('Stage 2 - Test') {
      steps {
        echo 'Running Unit Test.....'
        echo 'Running Integration Test.....'
        echo 'Running Aceptation Test.....'
      }
    }

    stage('Stage 3 - Deploy') {
      steps {
        echo 'Deploying artifact!!'
      }
    }

  }
}