node {
   stage('Preparation') {
      git 'https://github.com/tdunst83/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}