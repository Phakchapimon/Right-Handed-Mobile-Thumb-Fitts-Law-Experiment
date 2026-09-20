# Fitts-Law-Assignment
**Scenario:**
There are times when a user will use a mobile phone single-handedly while multitasking, like walking or holding an item. 
The user will need to use their dominant right hand to hold the mobile phone and try to click the target using only their right thumb. 

**HCI Problem:**
In mobile application interfaces, action controls are usually placed in the upper corners of the display. According to ergonomics, the human thumb has a limitation in reaching across the screen. Reaching targets on the far opposite side or the top of the screen requires physical stretching and re-gripping of the device. This increases target distance, increases the Index of Difficulty, slows down movement time, causes missing the action control, or leads to clicking the wrong button. 

How this project solves:
It provides data showing why app developers should place main controls in the lower thumb zone rather than the top corners to reduce movement time and misclicks. Also, it shows which distance and size of the button should be used to improve the user experience. 

**Innovation:**
Evaluate thumb reachability and motor performance across screen zones.
Every trial originates from a green START button in the bottom-right corner, which is the natural resting position for a right-handed thumb grip.

The target buttons will appear across thumb reach angles and across systematically varied distances [140px,280px,420px] and varied target widths [36px,60px,84px].
Accuracy: 108 trials (9 conditions × 12 repetitions)

**Screen Recording:**
https://github.com/user-attachments/assets/c1ccfa61-ad35-462d-9c3d-951bb450b6e4

**Results & Data Analysis:**
Scattered plot data:
<img width="400" height="497" alt="fitts_law_scatter_plot" src="https://github.com/user-attachments/assets/862d73f4-ea99-4fab-ae8a-9a0f98be50f5" />

108 trials data table:
[fitts_law_thumb_data_1789906876774.csv](https://github.com/user-attachments/files/32436283/fitts_law_thumb_data_1789906876774.csv)

9 conditions data table:
<img width="402" height="183" alt="Screenshot 2569-09-20 at 11 14 33 PM" src="https://github.com/user-attachments/assets/de8128c0-bb1e-41f4-8c0a-0e491ce29ccc" />

Fitts' Law Formula: 
MT = 178.59 + 140.43(ID) 

For 9 conditions: R^2=0.7455; Averaging the 12 trial repetitions per condition removes individual human trial-to-trial variance.

For 108 raw data: R^2=0.2184; Raw data includes human trial-to-trial variance across all 108 individual taps.

Intercept a = 178.59 ms

Slope b = 140.43 ms/bit

Fastest Condition: When the target was closest (A=140px) and largest (W=84px), the movement time was 390.33 ms. 

Slowest Condition: When the target was farthest (A=420px) and smallest (W=36px), the movement time increased to 647.67 ms.
