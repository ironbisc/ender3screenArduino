# ender3screenArduino
a breakdown of how to wire an ender 3 v1 screen to an arduino uno using u8g2

// U8g2 Constructor (adjust for your specific display)

U8G2_ST7920_128X64_F_SW_SPI u8g2(U8G2_R0, 10, 13, 11); // Adjust pins to your display configuration


//rotary inputs

  u8g2.begin(/*Select=*/ 7, /*Right/Next=*/ A1, /*Left/Prev=*/ A2, /*Up=*/ 9, /*Down=*/ 8, /*Home/Cancel=*/ 1); 



![Image](https://github.com/user-attachments/assets/332371e8-bb80-4daa-8b4c-a3366bb5d85b)

![Image](https://github.com/user-attachments/assets/754d7d35-f6ca-4b39-9eaf-d66e5440485d)

![Image](https://github.com/user-attachments/assets/b1324162-02c0-4e52-98ac-d62308a124dc)

![Image](https://github.com/user-attachments/assets/bc3d2e75-9bc3-4ce9-a915-629968ec0224)
