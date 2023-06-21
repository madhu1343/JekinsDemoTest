pipeline {
  agent any
  stages {
    stage('restore') {
      steps {
        pwsh 'dotnet restore'
      }
    }

  }
}