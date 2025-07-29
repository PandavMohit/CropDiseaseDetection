
---

# 🌱 Crop Disease Detection with Solution (Gemini 2.0 Flash)

### 📌 Project Overview

The *Crop Disease Detection with Solution* is a web-based application that uses *Gemini 2.0 Flash API* to analyze crop leaf images.
It can:

* Detect whether the uploaded image is a *leaf or not*.
* Identify *diseases like Leaf Spot, Rust, Blight* or detect *Healthy leaves*.
* Provide *treatment solutions* and *farming tips*.

This project is *powered by Google’s Gemini API* and *Gradio* for creating a simple interactive web app.
Perfect for *class submissions* and *AI/ML agriculture projects*.

---

### 🚀 Features

* ✅ *Leaf Verification* – Detects if the uploaded image is a valid leaf.
* ✅ *Disease Detection* – Identifies common crop diseases.
* ✅ *Solution Suggestions* – Provides fungicide or treatment recommendations.
* ✅ *Healthy Leaf Recognition* – Confirms if the crop is healthy.
* ✅ *Error Handling* – Returns an error if the image is not a leaf.

---

### 🛠 Tech Stack

* *Python 3.9+*
* *Gradio* (Web Interface)
* *Pillow (PIL)* (Image Handling)
* *Requests* (API Calls)
* *Gemini 2.0 Flash API* (Image Analysis)

---


---

### ⚡ How It Works

1. *User uploads a crop leaf image* in the Gradio interface.
2. *Gemini API* analyzes the image:

   * If *not a leaf →* returns an error.
   * If *a leaf →* returns:

     * Disease Name (or Healthy)
     * Description of the disease
     * Recommended Solution or Fungicide
3. *Formatted result* is displayed to the user.

---


---

### 🖼 Example Output

*Uploaded Image:* 🌿 Tomato Leaf

*AI Output:*


🌱 Crop: Tomato Leaf
⚠ Detected Disease: Leaf Spot
🔹 Description: Small brown or black spots caused by fungal infection
🔹 Recommended Solution: Apply copper-based fungicide, avoid overhead watering


---

### 🔑 API Key Setup

* This project uses *Google Gemini 2.0 Flash API*.
* Replace GEMINI_API_KEY in Crop Disease Detection.ipynb with your own API key:

python
GEMINI_API_KEY = "YOUR_API_KEY_HERE"


---


---

### 👨‍💻 Author

*pandav mohit*
📧 Email: pandavmohit09@gmail.com

---

