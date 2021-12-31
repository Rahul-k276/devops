pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/Rahul-k276/devops.git', branch: 'master', poll: true)
      }
    }

    stage('build') {
      steps {
        sh 'echo " build is running"'
      }
    }

    stage('sonar') {
      steps {
        sh 'echo " the sonar qube results"'
      }
    }

    stage('nexus') {
      steps {
        sh 'echo " artifact is stored in the nexus for future purposes"'
      }
    }

  }
}