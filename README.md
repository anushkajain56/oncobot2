# OncoBot 🩺🤖

OncoBot is an AI-powered assistant that helps patients inspect suspicious marks on their skin and guides them to nearby medical services. Using **computer vision** and **location-based services**, it detects potential signs of melanoma from user-submitted images and directs them to the nearest hospitals for further examination.

---

## 🚀 Features

- **Melanoma Detection:** Uses computer vision techniques (via OpenCV) to analyze skin images for potential melanoma.
- **Noise Reduction & Image Processing:** Employs a sequence of preprocessing steps to clean and enhance input images, preserving critical details in lesions.
- **Discord Integration:** Accessible through a **Discord bot**, making it easy for users to upload images and receive results in real-time.
- **Hospital Locator:** Integrates the **Google Maps API** to find and navigate to the nearest 5 hospitals based on the user’s address.

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries & Tools:**
  - OpenCV (image processing & computer vision)
  - Discord API (bot integration & user interaction)
  - Google Maps API (hospital navigation & geolocation services)

---

## 🧑‍💻 Project Structure

The project was developed by two collaborating teams:

1. **Computer Vision Team**
   - Built and fine-tuned the melanoma detection pipeline.
   - Explored various image preprocessing and analysis techniques.
   - Focused on preserving lesion data while removing noise.

2. **User Experience Team**
   - Integrated the bot into Discord for smooth interaction.
   - Enabled hospital lookup via the Google Maps API.
   - Designed user flows for accessibility and clarity.

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/OncoBot.git
cd OncoBot
pip install -r requirements.txt
```

---

## ▶️ Usage

Launch the bot:

```bash
python bot.py
```

On Discord:
- Upload an image of a suspicious skin mark.
- The bot will analyze the image and return results.
- Provide your address, and OncoBot will list the **5 nearest hospitals** for further examination.

---

## 📌 Roadmap

- [ ] Improve accuracy of melanoma detection using deep learning (e.g., CNNs).
- [ ] Add multi-language support for global accessibility.
- [ ] Expand medical database beyond hospitals (dermatologists, clinics).
- [ ] Develop a web & mobile interface alongside Discord.

---

## ⚠️ Disclaimer

OncoBot is **not a replacement for professional medical advice**. It provides guidance to encourage users to seek medical attention. Always consult a qualified healthcare provider for medical concerns.

---

