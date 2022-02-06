# API MOCKER
  ## About the Project
       CS561 Software Engineering Methods course project. This is an API Mocker for the openweathermap.org Weather service. 
       It is deployed on both AWS EC2 instance and on local host.
       
   ## Api Mocker on EC2 Instance  
       http://52.207.220.199:7878/data/2.5/weather
   ## Getting Started    
   ### Prerequisites
   * Here the project is built using Nodejs so for that it uses npm package manager.
      1) To set up Node.js on your Linux instance
        Install node version manager (nvm) by typing the following at the command line.
        
             curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
       2) We will use nvm to install Node.js because nvm can install multiple versions of Node.js and allow you to switch between them.
       
                . ~/.nvm/nvm.sh
            
       3) Use nvm to install the latest version of Node.js by typing the following at the command line.
            
              nvm install node
        4) The apimocker should be installed using the npm.
            
               node -e "console.log('Running Node.js ' + process.version)"
               
        5) git install 
        
          sudo yum install git   
        6) apimocker install
        
          npm install -g apimocker
               
               
        ## Installations   
  
        1) Clone the git repository 
        
          git clone  https://github.com/nithishrajapuram3/Assignment2.git
          
        2) Run the apimocker service 
        
          apimocker -c Config.json.
