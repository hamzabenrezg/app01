node {
   

    stage('Install node modules') {
        sh "npm install"
    }
  
    stage("Build") {
        sh "npm run build --prod"
    }
  

    stage("Test") {
        sh "ng test"
    }
  
    
}
