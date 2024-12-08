
  ## 🌍 Elephant-Care: Wearable IoT – Enabled Belt for Elephant protection & Emergency identification (24-25J-012)**

  
  🐘 Overview
  
<p>Elephants are endangered and play a vital role in maintaining the balance of their ecosystems. 
However, they frequently face significant threats from human activities, particularly collisions 
with trains. In India alone, approximately 150 elephants are killed annually due to such accidents 
(Gamage & Wijesundara, 2014).[1] These collisions not only diminish elephant populations but 
also pose severe risks to human safety and result in substantial economic losses due to property 
damage. To address this critical issue, implementing effective solutions like Elephant-Care is 
essential. Elephant-Care aims to leverage IoT technology to create a safer environment for both 
elephants and humans by preventing collisions through advanced detection, monitoring, and 
alert systems. This innovative approach integrates data transmission systems, biometric storage, 
data analysis, and an effective user interface to monitor elephant movements and predict 
potential collision hotspots. By utilizing a combination of real-time data collection, machine 
learning algorithms, and seamless communication networks, Elephant-Care can provide timely 
alerts to authorities, enabling preventive measures and promoting coexistence. And our system 
can detect detailed behavioral differences in elephants, such as distinguishing between lying 
down and walking. This capability allows for more accurate monitoring and tailored interventions. 
Overall, this multidisciplinary strategy offers a promising solution to a pressing conservation 
challenge, significantly reducing the incidence of collisions and supporting both wildlife 
conservation and human safety efforts.</p>


 ## Overall System Diagram
 
![Description of Image](https://github.com/KanishkaSemal/Elephant-Care-24-25J-012/blob/6c745472fd6fa836f4bc3a99467433350bac3ab9/Screenshot%202024-12-08%20183910.png?raw=true)




## 🔍 Key Features:

- Real-Time Monitoring: Tracks elephant movements and predicts collision risks.
- Behavioral Insights: Differentiates behaviors such as lying down versus walking for tailored interventions.
- User-Friendly Interface: Intuitive dashboards for authorities to make informed decisions.
- Biometric Storage: Secure and accurate elephant data for long-term conservation..

## Research Objective

- Wearable IoT Belt: Embedded with sensors that track the elephant's movement and health metrics.
- Real-Time Data Transmission: The data from the wearable device is continuously transmitted to a cloud-based system.
- Biometric Data Analysis: Data is analyzed using machine learning algorithms to detect specific elephant behaviors and predict potential collision zones.
- Alerting System: Alerts are sent to authorities or relevant bodies when potential risks are identified.
- Emergency Identification: In case of any emergency or behavioral anomaly, a real-time emergency alert is generated for immediate action.

## Group Members

1. Perera B.A.D.K.S – IT21202254
2. De Silva L.M.C - IT21301704


## Our Components

1. Data Transmission System.
2. Biometric Data Analysis & Real-Time Alerting System.
3. Track the Elephant Behavior And Emergency Responds.

## 1) Data Transmission System.

  🐘 Overview

  <p>The Data Transmission System is a critical component designed to facilitate the reliable 
and secure transfer of data collected from elephant body sensors to a remote receiver 
using a Lorawan Teachnology. This module leverages Arduino technology to create a robust system 
suitable for rural and remote areas with weak network signals, ensuring comprehensive 
and uninterrupted data flow.</p>


## System Diagram
![image](https://github.com/user-attachments/assets/68c7288d-7423-4068-9939-8e05ab0d3fe4)


## 2) Biometric Data Analysis & Real-Time Alerting System.

  🐘 Overview

  <p>The system begins with IoT devices collecting vital animal health data, such as heart rate, 
Body temperature, and Blood Oxeygen levels, and sending it to the API Gateway for validation. The API 
Gateway ensures the data's authenticity and correct format before routing it to the Time-Series 
Database for organized storage with precise timestamps. Post-storage, the data undergoes 
filtering to remove duplicates and noise, enhancing its quality for analysis. Advanced 
algorithms then analyze the refined data in real-time, identifying patterns and predicting future 
health conditions. These predictions generate real-time alerts and proactive recommendations 
for caretakers or veterinarians. User interaction is facilitated through a Live Analysis dashboard 
that displays current health status, historical trends, and recommendations in an intuitive 
format. Continuous security monitoring through Intrusion Detection Management safeguards 
the system and sensitive data, ensuring reliable health monitoring. This integrated approach 
provides a comprehensive and proactive solution for animal health management, delivering 
accurate and actionable insights through real-time data collection, advanced analytics, and 
robust security measures.</p>


## System Diagram
![image](https://github.com/KanishkaSemal/Elephant-Care-24-25J-012/blob/main/kanishka%20new.drawio.png?raw=true)




## 3) Track the Elephant Behavior And Emergency Responds.

  🐘 Overview

  <p>The biodata BPI and also all the raw data stored in the sensor’s database, which was captured 
from the elephant's care belt, Next, we use raw data processed into meaningful data and get 
output as information that stores in another database. By using that database, we can identify 
emergency situations using the information database, and the system will send notifications 
under the relevant elephant’s ID in the system. By using that information, we will be able to 
identify situations or anything that happens to elephants. We can identify those situations by 
receiving notification under the relevant elephant’s ID in the system. In my component, all the 
elephant’s data show as live charts and identify emergency situations. In an emergency 
situation, when identifying the data, there can be a delay in getting the data; hence, we can’t 
identify if anything happens to the elephant.  We can reduce data repetitions as a solution to 
the above problem. It helps reduce buffering time and increase the efficiency of the 
information.</p>


## System Diagram
![image](https://github.com/KanishkaSemal/Elephant-Care-24-25J-012/blob/main/menura.png?raw=true)







   



