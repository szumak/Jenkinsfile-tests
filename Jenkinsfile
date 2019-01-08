#!/usr/bin/env groovy

// new branch

pipeline {
  agent any
  stages {
    stage('init') {
       steps { 
         script {
           println "CHANGE_ID " + env.CHANGE_ID 
           println "CHANGE_BRANCH " + env.CHANGE_BRANCH 
           println "GIT_BRANCH " + env.GIT_BRANCH 
         }
       }
    }
  }
}
