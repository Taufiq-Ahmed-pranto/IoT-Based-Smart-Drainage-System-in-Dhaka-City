## IoT Based Smart Drainage System in Dhaka City

### Project Description
Waterlogging is a significant issue for the residents of Dhaka city. During the rainy season, even a moderate rainfall can cause flooding on the streets. The primary cause of this problem is the blockage of drainage systems due to the accumulation of waste and trash. In this project, we propose an IoT-based solution to address this issue. By implementing a smart drainage system, we aim to automatically detect and clear blockages without human intervention.

### Team Members:
- Taufiq Ahmed
  - Department of CSE, Daffodil International University
  - Email: taufiq15-11129@diu.edu.bd
- Fazle Rabby Talukder
  - Department of CSE, Daffodil International University
  - Email: fazle15-11022@diu.edu.bd
- MD. Al Amin Hosen
  - Department of CSE, Daffodil International University
  - Email: alamin15-11132@diu.edu.bd

### Keywords
Arduino, IoT, Smart drainage system, Water flow, Water level sensor

### Introduction:
Dhaka, being one of the most populous cities globally, faces severe waterlogging issues during the rainy season. With around 21 million residents, the city's drainage systems struggle to cope with the increasing volume of waste and rainfall. Traditional drainage systems are unable to effectively prevent waterlogging due to the blockage caused by accumulated waste. In this project, we propose an IoT-based solution to address this issue.

### Methodology:
#### Necessary Equipment:
1. **Arduino UNO**: 
    - Specifications:
        - Operating voltage: 5 volts
        - Input voltage: 7-12 volts
        - Digital I/O pins: 14 (6 provide PWM output)
        - Analog input pins: 6
        - Memory: Flash memory 32 KB, SRAM 2 KB, EPROM 1 KB

2. **Water Level Sensor**:
    - The sensor consists of ten exposed copper traces, five of which are power traces, and five are sensing traces. It works by varying its resistance according to the water level.

3. **Water Flow Sensor**:
    - Comprising a copper body, a water rotor, and a hall-effect sensor, the water flow sensor measures the flow rate of water by calculating the rotation of the turbine wheel.

4. **Relay**:
    - A relay is used as a smart switch to control IoT devices from a distance.

5. **DC Motor**:
    - A high voltage DC motor is used to pump water from resources and throw it at high pressure towards the blockage to clear the drains.

#### Proposed Method:
The proposed method comprises three sections: monitoring, decision, and prevention.
1. **Monitoring Section**:
    - Water level and water flow sensors are employed to detect drain blockages. These sensors send data to the Arduino system.
2. **Decision Section**:
    - The Arduino system interprets the water level and flow rate. Based on this data, it determines whether a blockage has occurred or not.
3. **Prevention Section**:
    - If a blockage is detected, a high voltage DC motor throws water at high pressure towards the blockage to clear the drain.

### Results:
The prototype is yet to be completed. Upon completion, it is expected to significantly reduce waterlogging issues in Dhaka city by automatically detecting and removing blockages without human intervention. This IoT-based solution will not only save time and resources but also improve the efficiency of the drainage system.

### Conclusion & Future Work:
The implementation of an IoT-based smart drainage system is crucial to address the waterlogging problem in Dhaka city. In the future, we plan to extend this system by integrating a water purification system to purify drain water and by introducing fish farming to meet the protein demand in the country.

### Acknowledgment:
The research is being conducted under the supervision of MD. Fahad Faisal, Assistant Professor, Department of Computer Science and Engineering, Daffodil International University. The authors would like to thank the professor for his support and guidance.

### References:
1. Keung, Kin Lok, Carman Ka Man Lee, K. K. H. Ng, and Chun-Kit Yeung. "Smart city application and analysis: Real-time urban drainage monitoring by iot sensors: A case study of Hong Kong." In 2018 IEEE International Conference on Industrial Engineering and Engineering Management (IEEM), pp. 521-525. IEEE, 2018.
2. Mowla, Qazi Azizul, and Mohammed Saiful Islam. "Natural drainage system and water logging in Dhaka: measures to address the problems." Journal of Bangladesh Institute of Planners ISSN 2075 (2013): 9363.
3. Tawhid, Khondoker Golam. "Causes and effects of water logging in Dhaka City, Bangladesh." TRITA-LWR master thesis, Department of Land and Water Resource Engineering, Royal Institute of Technology, Stockholm (2004).
4. Gupta, Apoorv, Aman Bansal, Rishab Gupta, Deepika Naryani, and Apoorvi Sood. "Urban waterlogging detection and severity prediction using artificial neural networks." In 2017 IEEE 19th International Conference on High-Performance Computing and Communications; IEEE 15th International Conference on Smart City; IEEE 3rd International Conference on Data Science and Systems (HPCC/SmartCity/DSS), pp. 42-49. IEEE, 2017.
5. Aarthi, M., and A. Bhuvaneshwaran. "IoT Based Drainage and Waste Management Monitoring and Alert System for Smart City." Annals of the Romanian Society for Cell Biology (2021): 6641-6651.
6. De Zoysa, Kasun, Chamath Keppitiyagama, Gihan P. Seneviratne, and W. W. A. T. Shihan. "A public transport system based sensor network for road surface condition monitoring." In Proceedings of the 2007 workshop on Networked systems for developing regions, pp. 1-6. 2007.
7. Akter, Sharmin, and P. Mahata. "Developing a smart irrigation system using arduino." International Journal of Research Studies in Science, Engineering and Technology 6, no. 1 (2018): 31-39.
