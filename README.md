# Containerized_Sentiment_analyser

## Instructions on how to build docker image and run the Sentiment Analyser

- Once the code is cloned, go to the python directory and run ```docker build t <<<username>>>/sentiment analysis logic .```
- Then run the image using ```docker run d p 5050:5000 <<<username>>>/sentiment analysis logic```
- Then navigate to the Java folder and run ```mvn install```
- Then run ```docker build t <<<username>>>/sentiment analysis web app .```
- Finally, run ```docker run d p 8080:8080 e SA_LOGIC_API_URL=http://192.168.99.100:5050 <<<username>>> /sentiment analysis web app```
