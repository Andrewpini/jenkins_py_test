pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        echo 'Cloning repository...'
        // Jenkins automatically checks out the repo in multibranch pipelines
      }
    }

    stage('Build - GCC') {
      steps {
        echo 'Simulating GCC build step...'
        // Replace with actual build command if needed
      }
    }

    stage('Build - IAR') {
      steps {
        echo 'Simulating IAR build step...'
        // Simulate another build toolchain
      }
    }

    stage('Tests') {
      steps {
        echo 'Running tests...'
        // Add test simulation or real test commands here
      }
    }

    stage('Package') {
      steps {
        echo 'Packaging artifacts...'
        // Simulate build artifacts
      }
    }
  }

  post {
    success {
      echo 'Build completed successfully ✅'
    }
    failure {
      echo 'Build failed ❌'
    }
  }
}
