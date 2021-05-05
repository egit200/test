// comentario

pipeline {
    
    
    // ejecutar desde cualquier nodo
    agent any
    
    // Fases
    
    stages {
        
        stage('Fase 1 Build')    {
            
            // pasos
            steps {
                
                echo "Fase 1 paso 1 ..."
                
            }
        }
        
          stage('Fase 2 Testing')    {
            
            // pasos
            steps {
                
                echo "Fase 2 paso 1 test unitarios"
                echo "Fase 2 paso 1 test integracion"
                echo "Fase 2 paso 1 test acptacion"
                
            }
        }
        
          stage('Fase 3 Deploy')    {
            
            // pasos
            steps {
                
                echo "Fase 3 paso 1 desplegando artefacto"
                
                
            }
        }
        
        
    }
    
}
