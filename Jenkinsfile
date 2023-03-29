pipeline {
    agent any

    stages{
        stage('fetch code') {
          steps{
              git branch: 'vp-rem', url: "https://github.com/devopshydclub/vprofile-repo.git"
          }  
        }

        stage('Build') {
             steps{
              git branch: 'vp-rem', url: "https://github.com/devopshydclub/vprofile-repo.git"
          }
        }
        stage('Test'){
             steps{
              git branch: 'vp-rem', url: "https://github.com/devopshydclub/vprofile-repo.git"
          } 

        }
         stage('Code Ananlysis'){
             steps{
              git branch: 'vp-rem', url: "https://github.com/devopshydclub/vprofile-repo.git"
          } 

        }
    }
}
