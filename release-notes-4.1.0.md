
#### Version Number
${version-number}

#### New Features
 - **SCMOD-10189**:  Updated Tomcat base image.  
  This has changes to meet the logging mandate by adding caf logging Tomcat juli project to Tomcat Java 11 image. 

#### Bug Fixes
 - **SCMOD-9495**: Adding the REQUIRED_DOCKER_HOST_TYPE=PRIVILEGED setting to the official-build.props file.  
  This enables the permissions package to be updated during the build.

#### Known Issues
 - None
