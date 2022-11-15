# # Jenkins Closing Task - Ynet News

## **The Purpose Of The App:**
- This App reads the news from the Ynet new service:
http://www.ynet.co.il/Integration/StoryRss2.xml .
- Using the spring boot, The App parses and Presents the Breaking
News XML in an HTML Table Format.
----
## **Steps To Running The App:**
**1. Clone This Repository.**
- git clone https://github.com/Dima-Nakhleh/Jenkins-Closing-Task-Ynet.git .
**2. Build The Project**
- mvn clean package .
**3. Run The Jar File**
-  java -jar target/YnetNewsApp-0.0.1-SNAPSHOT.jar
