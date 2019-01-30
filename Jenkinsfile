node {
   
   def BRANCH = 'master'
   def APPWORKSPACE = 'TechCrunchNews.xcworkspace'
    
    
    stage('Checkout') {
        
        // Checkout files.
        checkout([
            $class: 'GitSCM',
            branches: [[name: "${BRANCH}"]],
            doGenerateSubmoduleConfigurations: false,
            extensions: [], submoduleCfg: [],
            userRemoteConfigs: [[
                name: 'github',
                url: 'https://github.com/abhishekbedi1432/sample-helloworld-ant'
            ]]
        ])
    }
    
    stage('Ant Compile') {
        
    }      
}

