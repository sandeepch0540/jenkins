Pipeline{                                     
    Agent any
    Stages{
             Stages(“build”){
                Steps {
                        Echo “building the application..”
                }
         }
             Stage(“test”){
                        Steps { 
                             Echo  “testing the application..”
                   } 
}
Stage(“test”){
                        Steps { 
                             Echo  “deploying the application..”
                   }
}
}

