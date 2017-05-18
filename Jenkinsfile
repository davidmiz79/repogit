node {
   def filecontent
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/davidmiz79/repogit'
   }
   stage('ReadFile') {
      filecontent = readFile 'README.md' 
   }
   stage('Results') {
      echo "${filecontent}" 
   }
}