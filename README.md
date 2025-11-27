# Turbulence128-on-Phone

**First-ever real-time 128³ 3D pseudospectral turbulence simulation running natively on an Android phone**  
Pure Python + NumPy + PyTorch · zero external libs · ~1 FPS on Snapdragon 8 Gen 2

![image](https://github.com/user-attachments/assets/afea9b47-a7a9-4687-961b-d65eb6296cfa)

Live notebook with full code + outputs (just click the green button):  
[T128-on-Phone.ipynb](T128-on-Phone.ipynb) → **Open in Colab** button at the top

### What you’re looking at
- Grid: 128×128×128 (2,097,152 voxels)
- Full 3D incompressible Navier-Stokes via pseudospectral method
- Dealiasing, FFT convolutions, RK4 integration — all on CPU
- Interactive isosurface + vorticity visualization

### Run it on your phone (Termux)
```bash
pkg install python numpy pytorch torchvision
git clone https://github.com/JesseHouse/Turbulence128-on-Phone
cd Turbulence128-on-Phone
python turbulence_128_phone.py   # or open the notebook in Jupyter

 Proof it’s real - 400+ steps in the notebook: energy decay, FPS prints, live plots   - No GPU, no CUDA, no tricks — just a phone cooking continuum chaos  Broke the barrier. Phones can now simulate real turbulence in real time.   Next: 256³? 320³? Who’s stopping us.  If this blows your mind, throw a star or a coffee → paypal.me/rhouse84
