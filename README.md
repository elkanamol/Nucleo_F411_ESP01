# Nucleo_F411_ESP01

This App demonstrate Nucleo_F411RE  connecting to ESP01  (ESP8266) through UART and get enviroment data by BME280 over I2C bus. 
the unit send the data to ThingSpeak cloud and persent it by three chatrs.




# Connection wireing: 
![WhatsApp Image 2022-05-22 at 12 28 40 AM (1)](https://user-images.githubusercontent.com/57934787/169669581-43080e45-5627-4ad5-a25c-731cf9a92017.jpeg)
![WhatsApp Image 2022-05-22 at 12 28 40 AM](https://user-images.githubusercontent.com/57934787/169669587-78ca496b-3b8a-46de-bef5-f4e26c19ee58.jpeg)

![Schematic_SM32_Nucleo_F411RE_ESP32-01_2022-05-22](https://user-images.githubusercontent.com/57934787/169699221-1beb61e0-3614-4005-bc3c-66ea5888e913.png)
https://easyeda.com/editor#id=664e8544225641feb8eb29158b23b3a9

# CubeMX settings:

![image](https://user-images.githubusercontent.com/57934787/169699260-344ba341-4bb7-45ca-9f94-7e9c6f7b7b9d.png)


# float sprintf
Need to add float option in linker on project settings with sprintf() function. 

![image](https://user-images.githubusercontent.com/57934787/169691394-819e9ae9-e08a-4b19-bdc6-e1210e4ed898.png)


# TingSpeak charts:
![image](https://user-images.githubusercontent.com/57934787/169699354-d4ed7400-f8a1-4dc0-aed0-0f90521cbc90.png)


# Logic Analayzer scope trace:

![image](https://user-images.githubusercontent.com/57934787/169691432-7db5ed55-56d0-4acb-91d2-bef70138cef8.png)

