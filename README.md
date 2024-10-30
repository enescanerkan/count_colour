# COLOR DETECTION APPLICATION

This Python application captures live video from a webcam and detects specific colors in the video stream. (Bu Python uygulaması, bir web kamerasından canlı video alır ve video akışındaki belirli renkleri tespit eder.) The application is developed using libraries such as OpenCV and Tkinter. (Uygulama, OpenCV ve Tkinter gibi kütüphaneler kullanılarak geliştirilmiştir.)

## USAGE

### INSTALLATION OF REQUIRED LIBRARIES
Before running the application, install the required libraries by executing the following command: (Uygulamayı çalıştırmadan önce gerekli kütüphaneleri aşağıdaki komutu çalıştırarak kurun:)

```bash
pip install opencv-python pillow

Then, run the application using the command:

python count_colors.py

Note: Upon running the application, the webcam feed will automatically open. (Not: Uygulamayı çalıştırdığınızda, web kamerası görüntüsü otomatik olarak açılacaktır.)

Color Detection and Counting
The application, when executed, detects specific colors (Green, Blue, Red, Yellow, Orange, Purple, Gray, Pink) in the webcam feed and updates the count of these colors in real-time. (Uygulama çalıştırıldığında, web kamerası görüntüsündeki belirli renkleri (Yeşil, Mavi, Kırmızı, Sarı, Turuncu, Mor, Gri, Pembe) tespit eder ve bu renklerin sayısını gerçek zamanlı olarak günceller.)

Core Functionality
The basic logic is that a line drawn in the center of the screen counts the colors passing over it. (Temel mantık, ekranın ortasında çizilen bir çizgi üzerinden geçen renkleri saymaktır.) If the point of the centroid of the detected color crosses the green line, the color count is incremented and added to the user interface. (Eğer tespit edilen rengin ağırlık merkezindeki nokta yeşil çizgiyi geçerse, renk sayısı artırılır ve kullanıcı arayüzüne eklenir.) Users can control the application using buttons such as Start, Stop, and Exit. (Kullanıcılar, Başlat, Durdur ve Çıkış gibi butonlarla uygulamayı kontrol edebilirler.)

Features
Color Detection: The application can detect specific colors such as green, blue, red, yellow, orange, purple, gray, and pink. (Renk Tespiti: Uygulama, yeşil, mavi, kırmızı, sarı, turuncu, mor, gri ve pembe gibi belirli renkleri tespit edebilir.)
Color Counting: It updates the count of detected objects for each color, providing a real-time display of object counts. (Renk Sayımı: Tespit edilen nesnelerin her bir renk için sayısını güncelleyerek, nesne sayılarının gerçek zamanlı bir görüntüsünü sunar.)
User Interface: The application offers a simple and user-friendly experience using the Tkinter GUI. (Kullanıcı Arayüzü: Uygulama, Tkinter GUI kullanarak basit ve kullanıcı dostu bir deneyim sunar.)



## Images

![renksayma](https://github.com/user-attachments/assets/aa57e690-3400-4bf1-823b-e6bd244c0ef2)

![arayüz](https://github.com/user-attachments/assets/012db87e-450e-43c7-ba6c-c5529b8070bf)
