# 🎤 Speech Enhancement GAN 

A GAN-based approach for enhancing speech from noisy audio.

---

## 🔹 About
This project is a *GAN-based model for speech enhancement*, trained to remove noise from audio signals.  

It is based on an earlier implementation, with *modifications and improvements*, including:
- ✅ Updated training pipeline  
- ✅ Cleaned dataset handling  
- ✅ Additional documentation  
- ✅ Dual licensing for clarity  
## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<Sirichandana-jpg>/<speech-enhancement-gan-experiments>.git
cd <speech-enhancement-gan-experiments>

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt

###3️⃣ Train the Model
```bash
python train.py --dataset data/noisy --clean data/clean

###4️⃣ Test the Model
```bash
python test.py --input data/test_noisy
