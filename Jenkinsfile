pipeline {
	agent any 
	stages {
		stage ("welcome with file operation") {
			steps {
				script {
					File file = new File("/tmp/file1.txt")
          println file.readLines()
				}
			}
		}
	}
}
