# Turbulence128-on-Phone

World-first real-time 128³ 3D pseudospectral turbulence simulation running natively on an Android phone
Pure Python + NumPy + PyTorch, no CUDA, no GPU, approximately 1 FPS on Snapdragon 8 Gen 2

Full notebook (complete code + live outputs + plots)
[T128-on-Phone.ipynb](T128-on-Phone.ipynb)
Click the green "Open in Colab" button at the top of the notebook to run it instantly in your browser.

Real phone run - 400 steps at 1.17 FPS
![400 steps at 1.17 FPS on phone]
![image](https://github.com/user-attachments/assets/3387478b-1342-4c7d-b85c-dee1518f33c2)


Run it yourself on Android (Termux)
pkg update
pkg install python python-numpy pytorch ffmpeg libjpeg-turbo -y
git clone https://github.com/JesseHouse/Turbulence128-on-Phone
cd Turbulence128-on-Phone
python turbulence_128_phone.py

320³ in progress
If this blew your mind, drop a star or buy me a coffee: https://paypal.me/rhouse84
