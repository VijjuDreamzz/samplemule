pipeline {
	  agent any
	  stages {
	    stage('compile') {
	      steps {
	         // git branch: 'master',
	         //    url:'https://github.com/lerndevops/samplejavaapp.git'
	          sh 'mvn compile'
	            }
                              }
	    stage('munit') {
	      steps {
	          sh 'mvn test'
                    }
	                   }
	    stage('package') {
	      steps {
	          sh 'mvn package'
                    }
	                     }
                 }
          }
