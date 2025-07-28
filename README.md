# Design and Development of a Low-Cost Hearing Aid Using Arduino
## Authors: 
Mohamed Elmogtaba, Adam Hamid Mohamed Elzein, Ibrahim Sami Bukhari Elsir Babiker  
**Supervisor:** Dr. Abdul Razzaq  

## 1. Introduction  
Hearing loss affects 466 million people worldwide (WHO). Traditional hearing aids cost $1,000-$4,000, making them inaccessible in developing regions...

## 2. Methodology
### Hardware Components:
| Component       | Specification       | Cost  |
|-----------------|---------------------|-------|
| Arduino Nano    | ATmega328P          | $3.50 |
| MAX9814 Mic     | 60dB Gain           | $2.80 |
| PAM8403 Amp     | 3W Output           | $1.20 |
| Li-ion Battery  | 18650 3.7V 2000mAh  | $2.50 |

### Signal Processing Flow:
Microphone → Analog Read → Noise Filtering (FFT) → Amplification → Audio Output
