# FF5_REAL_TIME

This repository contains code to calculate the Fama French 5 Factors on a daily basis using raw daily pricing data and Zacks Fundamentals Data. The significance of this implementation is its ability to provide real-time deployment and testing of trading signal exposures.

Traditionally, the Fama French data library offers factor data up to a point that is two months prior. Our implementation updates these factors based on the most recent pricing data available, providing users with the most current information.

The entire process, from data loading to factor calculation, has a runtime of approximately 3-4 minutes. This efficiency makes our implementation particularly useful for researchers and traders seeking to construct the Fama French 5 Factors quickly and accurately. Therefore, users can base their decisions on the most up-to-date data, enhancing the effectiveness of their trading strategies.

Due to the difference in data collection between Zacks and Compustat our Fama French Portfolio sample is slightly different from Fama and French's.  

![image](https://github.com/shantanu2383/FF5_REAL_TIME/assets/123670210/c9f27e77-da5e-40e9-b707-907a470e2011)
![image](https://github.com/shantanu2383/FF5_REAL_TIME/assets/123670210/d14f05f1-b939-447a-bfa5-7578147c97c7)
![image](https://github.com/shantanu2383/FF5_REAL_TIME/assets/123670210/389fff15-c112-4978-993d-62a53a000b38)
![image](https://github.com/shantanu2383/FF5_REAL_TIME/assets/123670210/6c50839d-a08f-4be0-8136-bed17ac081f9)
![image](https://github.com/shantanu2383/FF5_REAL_TIME/assets/123670210/9fb513c8-f106-4cd0-bc16-fde59d95d9e4)




