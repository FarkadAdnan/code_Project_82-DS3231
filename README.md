# code_Project_82-DS3231
Chapter 3 code_Project_82 The second part 2 of "The Arduino World Book" code_Project_82
-  By:Farkad Adnan فرقد عدنان - 
 -E-mail: farkad.hpfa95@gmail.com 
-inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
- FaceBook: كتاب عالم الاردوينو 
- inst : arduinobook
1. #كتاب_عالم_الاردوينو
2. #كتاب_عالم_الآردوينو

-https://www.facebook.com/profile.php?id=100002145048612-
-https://www.instagram.com/farkadadnan/
-https://www.linkedin.com/in/farkad-adnan-499972121/

 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>

# General structure
An Arduino Library for EASY communication with DS3231 I2C RTC Clock and Atmel AT24C32 I2C EEPROM commonly found on the same board. Implements setting, getting the time/date, setting, checking and clearing alarms, and dead-easy circular-buffered logging of data with timestamp.
![Capture](https://user-images.githubusercontent.com/35774039/162672164-d1c02d42-806e-4409-8755-47c59dace379.JPG)

# library 

```
#include <Wire.h>
#include "RTClib.h"
RTC_DS3231 rtc;
```
# شريحة أو رقاقة DS3231 RTC عن قرب

![DS3231-RTC-Module-24C32-EEPROM-I2C-Address-Selection-Jumpers](https://user-images.githubusercontent.com/35774039/162673162-00b855d8-4d43-49bd-87bc-90bc982b9416.jpg)
![2222I2C-Address-selection-jumpers-on-DS3231-module-1](https://user-images.githubusercontent.com/35774039/162673172-8a0b5d54-81bb-4121-b80a-8657bd35db99.jpg)

# المذبذب الكريستالي التعويضي لدرجة الحرارة (TCXO)

![TCXO-Crystal-Oscillator-Compensation](https://user-images.githubusercontent.com/35774039/162673230-30c74f4d-a1cf-4cc3-a64f-f7dda863d3e2.png)


