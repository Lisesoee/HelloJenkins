pipeline{
    agent any
    triggers {
        pollSCM("*****") // wil trigger wheneve there is a change in VC (pull from VC to check every minute)
    }
    stages{
        stage("MyFirstState"){
            steps {
                echo "Yay, we are running!"
            }
        }
        // stage("Build"){
        //     steps{
        //         sh "dotnet build myproject.csproj" // commandline tool to run project                
        //     }            
        // }
        // stage("Test"){
        //     steps{
        //         sh "dotnet build myproject.csproj" // commandline tool to run project                
        //     }            
        // }
        // stage("Delivery"){
        //     steps{
        //         echo "========executing A========"
        //     }
        //     post{
        //         always{
        //             echo "========always========"
        //         }
        //         success{
        //             echo "========A executed successfully========"
        //         }
        //         failure{
        //             echo "========A execution failed========"
        //         }
        //     }
        // }
    }
    // post{
    //     always{
    //         echo "========always========"
    //     }
    //     success{
    //         echo "========pipeline executed successfully ========"
    //     }
    //     failure{
    //         echo "========pipeline execution failed========"
    //     }
    // }
}