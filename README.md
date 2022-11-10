### Quick set up Eslint with airbnb style guide  

1. Installing Eslint:  
    `npm install eslint --save-dev`
    
2. Installing an Airbnb style guide:  
    `npm install eslint-config-airbnb --save-dev`  
    
3. Running the eslint configuration:  
    `./node_modules/.bin/eslint --init`  
    
    If you prefer JSON, the *.eslintrc.json* file should look like this:  
    ```
    {    
        "extends": "airbnb"   
    }
     ```  
     
4. To check the entire project by running the following command:  
    `./node_modules/.bin/eslint .`
