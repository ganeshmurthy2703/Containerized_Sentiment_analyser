# JAVA_API

## What does this code do?
- This code provides the backend functionality in springboot for our Sentiment Analyser app. 

## How to run?
- To start up the Springboot app you need JDK8 and Maven installed and also the environment variables need to be set.
- run ``` mvn install ``` . This will generate a ```target``` folder in ```sa-webapp```  Therein you will find your Java application packaged as a nice jar: ```sentiment-analysis-web-0.0.1-SNAPSHOT.jar```

- In order for the jar to run successfully, make sure the Python API is running on port 5000 and then navigate to the ```target``` folder and type in ```java -jar sentiment-analysis-web-0.0.1-SNAPSHOT.jar --sa.logic.api.url=http://localhost:5000/```

## Make sure the Windows Defender or any other firewalls configured will allow to open that port up!
