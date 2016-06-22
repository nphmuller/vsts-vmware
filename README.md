# vso-vmware

# To build Java code

    - Ensure you have instilled the maven
    - compile - mvn compile
    - run test  -   mvn test    
    - code coverage -   mvn test verify
            Go to _build ( _build\testReports\codecoverage ) folder on root directory to check the code coverage

# To build JS / TS  code
    
    - Ensure you have node.js installed
    - code build - gulp
    - test run - gulp test
    
# To package
    
    - Run 'gulp'.
    - Run 'mvn package'.
    - Clean node modules and restore production packages with 'npm install --production'.
    - Copy node_modules to build directory.
    - Deploy task with tfx.
    