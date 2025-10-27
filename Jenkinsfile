pipeline{
    agent any

    stages{
        stage("Build"){
            steps{
                echo "========executing A========"
            }
            post{
                always{
                    echo "========always========"
                }
                success{
                    echo "========Build executed successfully========"
                }
                failure{
                    echo "========Build execution failed========"
                }
            }
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========Pipeline executed successfully ========"
        }
        failure{
            echo "========Pipeline execution failed========"
        }
    }
}