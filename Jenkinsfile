pipeline {
        agent any
        stages{
            stage("build"){
                steps{
                    echo "building the project"
                }
            }
            stage("test"){
                steps{
                    echo "testing the project"
                }
            }
            stage("deploy the project"){
                steps{
                    zsh "brew services info jenkins"
                }
            }
        }
}