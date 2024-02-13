pipeline {
	agent any 
	stages {
		stage ("welcome with file operation") {
			steps {
				script {
					File file = new File("/tmp/file.txt")
          println file.readLines()
          for(line in file.readLines()){
          println line
          }
        }
			}
		}
	}
}
