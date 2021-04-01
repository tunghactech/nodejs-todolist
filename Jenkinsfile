pipeline {
     agent { label 'm' }
     stages {
          stage("clone stage") {
               steps {
                    git 'https://github.com/tunghactech/nodejs-todolist.git'
               }
          }
          stage("build stage") {
               steps {
                    sh 'docker build -t nodejs-todolist .'
               }
          }
     }
}
ode1
