# Real-Time Object Detection on Edge Devices with YOLOv4-Tiny  

## 📌 Project Overview  
This project analyzes the suitability of **YOLOv4-Tiny** for real-time object detection on **edge devices** like the Raspberry Pi. The lightweight architecture of YOLOv4-Tiny enables high-speed inference, making it ideal for resource-constrained hardware. This work is presented in the form of a **college task**, focusing on the architectural advantages and performance optimizations of YOLOv4-Tiny over vanilla YOLOv4.  

---

## 🚀 Key Features  
1. **Lightweight Architecture**:  
   - YOLOv4-Tiny uses fewer layers and smaller backbones, making it faster and more efficient for edge deployment.  
2. **Real-Time Performance**:  
   - Optimized for speed and efficiency while maintaining acceptable accuracy for real-world applications.  
3. **Edge Device Optimization**:  
   - Tested on devices like Raspberry Pi 4B for optimal detection.

---

## 🛠 Architecture and Performance Enhancements  
### YOLOv4-Tiny Architecture  
1. **Backbone**:  
   - CSPDarknet53-Tiny for efficient feature extraction.  
2. **Neck**:  
   - Feature Pyramid Network (FPN) for feature pooling.  
3. **Head**:  
   - Dual-scale detection for large and small objects using 13×13 and 26×26 grids.  

### Performance Enhancements  
1. **Fewer Parameters**:
   - ~6 million compared to ~63.6 million in YOLOv4.  
3. **Simpler Activation**:
   - Uses LeakyReLU instead of Mish activation for faster computation.  
5. **Quantization and Pruning**:
   - Reduces model size and increases speed for edge deployment.  
7. **TPU Acceleration**:
   - Compatible with hardware like Google Coral for faster inference.  

---

## 🛠 Usage  
### Dependencies  
- **Python**: 3.8+  
- **Libraries**: `tensorflow-lite` ,`darknet` , `numpy`, `opencv-python`
- **Hardware**: Raspberry Pi 4B 

---

## 📄 License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  
