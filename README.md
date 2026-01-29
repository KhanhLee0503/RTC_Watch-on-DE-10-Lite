# RTC_Watch-on-DE-10-Lite
This is a personal project designing an RTC Watch and implementing it on DE-10 Lite

# Product Requirement
## 1. Overview
<img width="1041" height="375" alt="image" src="https://github.com/user-attachments/assets/e0ede8a6-a6d3-4a48-a28d-5cd22ffd244c" />

## 2. I/O Pins
<img width="884" height="390" alt="image" src="https://github.com/user-attachments/assets/c3fbd64c-60fc-4f8f-ad69-cd328f412596" />

## 3. Features
1. Able to display hour, minute, second, day, month, year
- In clock mode, if the **incr** button is pressed, the watch will display day, month, year. Otherwise, hour, minute, second are displayed
2. Can adjust hour, minute, second, day, month, year by using 2 buttons (set, incr)
- When the **set** is pressed, the watch will change mode from clock to adjusting parameters
- The order of the parameters are sec -> minute -> hour -> day -> month -> year -> clock
- In adjusting mode, the **incr** button is used to increase value of adjusted objects. The adjusted object is blinked, other objects don't change their displayed value
  
