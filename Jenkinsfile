pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test1') {
      steps { sh 'node --version' }
    }
    stages('Test2'){
		steps { sh 'node -e "console.log('Hello World')"'}
    }
  }
}
