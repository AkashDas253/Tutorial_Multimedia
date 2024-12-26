## **Equations in Sound Concepts**

#### **1. Frequency and Wavelength Relationship**  
The relationship between the speed of sound (`v`), frequency (`f`), and wavelength (`λ`) is:  

$$  
v = f \cdot \lambda  
$$  

- **`v`**: Velocity of sound (m/s)  
- **`f`**: Frequency (Hz)  
- **`λ`**: Wavelength (m)

---

#### **2. Decibels (Sound Amplitude or Intensity)**  
Sound intensity in decibels (dB) is calculated as:  

$$  
L = 10 \cdot \log_{10} \left( \frac{I}{I_0} \right)  
$$  

- **`L`**: Sound level in decibels (dB)  
- **`I`**: Intensity of the sound wave (W/m²)  
- **`I_0`**: Reference intensity (usually `10^(-12)` W/m² in air)  

For comparing two sound intensities, the formula becomes:  

$$  
L = 20 \cdot \log_{10} \left( \frac{P_1}{P_2} \right)  
$$  

- **`P_1, P_2`**: Sound pressures (Pa)

---

#### **3. Sampling Theorem (Nyquist Theorem)**  
To accurately digitize a sound, the sampling rate (`f_s`) must be at least twice the maximum frequency (`f_max`) of the signal:  

$$  
f_s \geq 2 \cdot f_{max}  
$$  

- **`f_s`**: Sampling rate (Hz)  
- **`f_max`**: Maximum frequency of the sound (Hz)  

---

#### **4. Quantization Levels**  
The number of quantization levels (`Q`) is given by:  

$$  
Q = 2^n  
$$  

- **`n`**: Bit depth (number of bits per sample)  

Higher `Q` values provide finer detail in the sound representation.

---

#### **5. MIDI Time-Stretching Formula**  
For MIDI, the relationship between note duration (`T`) and tempo (`BPM`) is:  

$$  
T = \frac{60}{BPM}  
$$  

- **`T`**: Duration of one beat (seconds)  
- **`BPM`**: Beats per minute  

This equation determines the timing of MIDI events.

---
