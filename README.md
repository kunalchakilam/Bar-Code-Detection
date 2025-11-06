# 📸 Bar-Code Detection System  

### 🧠 **Course:** CS 3107 - Digital Image Processing (DIP)  
### 🏷️ **Project Name:** Barcode Detection  
### 👨‍💻 **Team Members:**  
- Chakilam Kunal – SE22UCSE0631  
- Chakrika Nukala – SE22UCSE0642  
- C. Surya Tej – SE22UCSE0653  
- Challa Gomathi – SE22UCSE0664  
- Challa Shishir – SE22UCSE0675  

---

## 📝 **Abstract**  
The **Barcode Detection System** identifies and decodes various barcode types from images and real-time video streams. It combines **image preprocessing**, **feature detection**, and **decoding** techniques for high accuracy using **OpenCV** and **pyzbar**.  

Key implementations:  
- 📁 Barcode detection from uploaded images  
- 🎥 Real-time barcode detection using webcam  

---

## ⚙️ **Technologies Used**
- **Language:** Python 🐍  
- **Libraries:** OpenCV, Pyzbar, NumPy  
- **Tools:** Webcam, IDE (PyCharm / VSCode)  

---

## 🧩 **Concept Overview**
Barcodes are machine-readable patterns used across industries for tracking and automation.  
- **1D Barcodes:** UPC, Code 39, Code 128  
- **2D Barcodes:** QR, Data Matrix, Aztec  
- **Others:** PDF417, MaxiCode  

---

## 🌟 **Key Features**
1. **Preprocessing** 🖼️  
   - Grayscale Conversion  
   - Edge Detection (Canny Algorithm)  
   - Feature Extraction (ORB)  

2. **Detection** 🎯  
   - ORB Feature Matching  
   - Bounding Box Generation (optional)  

3. **Decoding** 🧾  
   - Pyzbar for barcode type and data extraction  

---

## 🧠 **Code Workflow**
1. 📥 Import Libraries  
2. 🖼️ Read Image  
3. ⚫ Convert to Grayscale  
4. ⚡ Apply Edge Detection  
5. 🔍 Detect Features (ORB)  
6. 🧩 Decode Barcodes using Pyzbar  
7. 🖋️ Draw Bounding Boxes  
8. 👀 Display Image or Live Webcam Feed  

---

## 📊 **Performance**
- Tested on **custom** and **Roboflow datasets**  
- Achieved strong **detection accuracy** even on noisy and low-light images  
- Operates at ~30 FPS for real-time webcam detection  

---

## 🚀 **Deployment Options**
- 🖥️ **Local Deployment:** Run directly on a system  
- ☁️ **Cloud Deployment (Future):** Enable distributed barcode detection via APIs  
- 🔌 **Hardware Integration:** Use in handheld barcode scanners  

---

## 🏭 **Applications**
- 🛒 Retail & Inventory Management  
- 🚚 Logistics and Supply Chain  
- 🏥 Healthcare for patient/medicine tracking  
- 📚 Library & Education systems  

---

## 🔮 **Future Scope**
- 🤖 AI-based damaged barcode recovery  
- 📦 Support for 3D & embossed barcodes  
- ☁️ Cloud-based barcode analysis  

---

## 🧩 **Technical Innovation**
- Combines **Canny Edge Detection** and **ORB Feature Extraction**  
- Ensures real-time efficiency (30 FPS)  
- Integrates **Pyzbar** for multi-format compatibility  

---

## 🏁 **Conclusion**
The **Barcode Detection System** is a reliable, efficient, and scalable solution for barcode recognition across industries. Its real-time capability and modular structure make it a strong base for future AI and cloud-powered applications. 🌐  
