pipeline {
    agent any 
        stages {
          stage('ansible-test') {
              steps {
                  sh "ansible localhost -m ping"  
              }
          }
          stage('ansible-clone') {
              steps {
                  echo "clone completed"
                  sh "ansible-playbook nodejs_setup.yml -e nodejs_version=nodejs10"
              }
          }
          stage('nodejs-version') {
              steps {
                  
                  sh "node-v"
              }
          }
        }
    
}
