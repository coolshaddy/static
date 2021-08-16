// Script //
node {
  stage('Build') {
    sh 'mkdir /home/sunday'
      }
        stage('Test') {
	  sh 'make check'
	    junit 'reports/**/*.xml'
	      }
	        stage('Deploy') {
		  sh 'make publish'
		    }
		    }
