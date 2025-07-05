pipeline{
        agent any
           stages{
                 stage("Build"){
                               steps{
                                     echo "start Building"
                                     sh "npm install"
                                     sh "npm run build"
                                     echo "Building Completed"
}
}        
}
}