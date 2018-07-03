pipeline {
  agent any
  stages {
    stage('code checkout') {
      steps {
        git(url: 'https://github.com/PrashantGitRepo/TestRepo.git', branch: 'master', poll: true)
      }
    }
    stage('code build') {
      steps {
        echo 'Code Build Successfully'
      }
    }
    stage('deploy') {
      steps {
        echo 'Successfully deployed'
      }
    }
  }
}