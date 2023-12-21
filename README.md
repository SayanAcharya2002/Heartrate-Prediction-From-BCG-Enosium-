# Hybrid Model For BCG Signal Analysis

**Team: Robo_boys**

**Team members: Tanvir Alam, Sayan Acharya, Ritodeep Sikdar, Aditya Ganguly**

**Problem Statement :**
Contactless vitals monitoring is the next big frontier in MedTech. Design and develop an algorithm to measure vitals such as pulse and breathing rate from data collected contactlessly.

**Problem Description :**
*In the Mesopotamian epic Gilgamesh written in 2600 BC, the hero-king Gilgamesh uttered the following lament at the death of his best friend Enkidu: “I touch his heart, but*
*it does not beat at all.” This is the earliest reference acknowledged by historians that shows humankind understood that heartbeat is an important indicator for health and*
*well-being and that it is measurable by (contact) sensing. 21st century advances in Sensors, AI and Edge computing have ushered in the era of contactless vitals*
*monitoring using smart watches, clothes, shoes and mattresses. Ballistocardiogram (BCG) captures the ballistic forces of the heart caused by the sudden ejection of blood*
*into the great vessels with each heartbeat, breathing, and body movement. In practice,BCG sensors are placed under bed mattresses for sleep tracking, and hence several*
*factors, e.g., mattress thickness, body movements, motion artifacts, bed-partners, etc.can deteriorate the signal. Accounting for these factors, design and develop an*
*algorithm to measure:*

*1. Bed occupancy*
*2. Heart rate*
*3. Breathing rate*
*4. Individual heartbeat*
*5. Motion artifacts*



# **OUR APPROACH**

1. *We applied Sinusoidal Regression with Adaptive Learning for detecting J peaks and reducing noise in the signal.*
2. *Moreover we used time series signal analysis with Dragonfly optimization for detecting J peaks without considering noise.*
3. *We designed a Deep Learning model which tells us the presence of J peaks within a particular window length.* 
4. *Finally, we developed algorithms for finding heart rate, breathing rate, motion artifact and bed occupancy.*

Since the dataset prediction folder contains more than 100 files we could not upload it on Github.However we are providing the google drive link as well as the ZIP file.

Note : If there is no notinbed csv file this means that there was no detected point where he was out of his bed



**Dataset Prediction Link : https://drive.google.com/drive/folders/1mN0qr2Ryk-WiPWGsjK1m0RTeAeHg0GhU?usp=sharing**
