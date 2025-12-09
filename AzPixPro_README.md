# **AzPix Pro — Intelligent File Recovery & PNG-based Data Container**

AzPix Pro is an innovative cross-platform tool designed to encode any file into a PNG image using advanced LZMA2/XZ compression and a custom binary container format — and then restore the original file back with full integrity.  
The project includes Android and Windows versions with a unified core engine.

---

## 🚀 **Features**
- Encode any file into a single PNG image (AzPix PNG)
- Restore original files with lossless accuracy
- Support for large files via chunking architecture
- Intelligent headers and CRC-based integrity checks
- LZMA2/XZ high-ratio compression
- Clean, simple, modern UI (Android & Windows)
- Offline operation — no internet required
- Cross-platform AzPix Core Engine

---

## 📱 **Android Version**
- Built with **Kotlin** and **Jetpack Compose**
- “Encode”, “Decode”, and “Camera Transfer” modules
- Saves AzPix PNGs to internal storage  
- Reconstructs files fully from AzPix images  
- Planned feature: decode files directly **from camera** for offline transfer

---

## 🖥 **Windows Version**
- Built with **C# / .NET (WPF)**
- Transparent custom UI, stylized buttons, and dark aesthetic
- Encodes & decodes using AzPixCore.dll
- Uses drag-and-drop for user convenience
- High compression & instant preview support

---

## 🧠 **How It Works**
1. Input file is compressed with **LZMA2/XZ**  
2. A custom binary header is added (magic bytes, size, CRC, metadata)  
3. Data is split into RGB channels and mapped into a PNG image  
4. Decoder reads header → extracts payload → validates CRC → restores file  

PNG is chosen because:
- It is lossless  
- Supported everywhere  
- Easy to transmit, store, and display  

---

## 🛠 **Tech Stack**
**Languages:** Kotlin, C#, Python  
**Frameworks:** Jetpack Compose, .NET WPF  
**Compression:** LZMA2 / XZ  
**Core Engine:** Custom PNG-based data container  
**Tools:** Android Studio, Visual Studio, FFMPEG (optional), Git  
**Architectures:** MVVM (Android), modular core engine  

---

## 🧩 **Use Cases**
- Offline file transfer between devices  
- Secure file archiving  
- Educational demonstrations of data encoding  
- Recoverable visual data containers  
- AI-assisted file restoration (planned – Bria FIBO integration)

---

## 🔮 **Future Enhancements**
- AI-powered corrupted-image recovery  
- Camera-based real-time decoding  
- Bria FIBO model integration for intelligent pixel restoration  
- Web-based encoder/decoder version  
- Improved UI/UX for professional workflows  

---

## 👨‍💻 **Developer**
**Azamat — InfoSchoolUz**
