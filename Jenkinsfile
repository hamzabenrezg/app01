node {
   

    stage('Install node modules') {
        sh "npm install"
    }

    stage("Test") {
        sh "ng test"
    }

    stage("Build") {
        sh "npm run build --prod"
    }
    
    
}
