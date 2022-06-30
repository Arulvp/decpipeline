pipeline {
    agent any
        stages {
            stage ('one') {
                steps {
                    echo "Build one"
                }
            }
            stage ('two') {
                steps {
                echo "Build two"
                }
            }
            stage ('three') {
                steps {
                    input ("shall proceed")
                }
                
            }
        }
}
