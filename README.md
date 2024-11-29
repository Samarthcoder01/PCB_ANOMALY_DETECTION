# 🌟 PCB Thermal Anomaly Detection  

In the intricate world of electronics, ensuring the **quality and reliability** of Printed Circuit Boards (PCBs) is paramount. Our **PCB Thermal Anomaly Detection** project leverages **cutting-edge machine learning techniques** to identify and classify thermal anomalies in PCBs, helping manufacturers maintain **high-quality standards** in production.

---

## 📋 **Introduction**  

**PCB Thermal Anomaly Detection** is an innovative solution designed to **automate** the process of identifying thermal anomalies in PCBs. Using **deep learning models**, this project enhances the **efficiency and accuracy** of quality control in PCB manufacturing. It’s ideal for:  
- **Electronics manufacturers**  
- **Researchers**  
- **Tech enthusiasts**  

This project integrates **advanced anomaly detection** techniques into workflows with ease.

---

## ✨ **Features**  

1. **Automated Thermal Anomaly Detection**: Quickly identifies issues like hotspots and overheating.  
2. **High Accuracy**: Employs **state-of-the-art deep learning models** for precise anomaly classification.  
3. **User-Friendly Interface**: Built with **Pygame**, offering an intuitive interface for detection workflows.  
4. **Real-Time Analysis**: Supports live video feed processing for real-time monitoring.  
5. **Graphical Visualization**: Displays interactive **accuracy** and **thermal intensity graphs** for insights.  
6. **Extensible**: A modular design allows for easy addition of new anomaly types and models.

---

## 🚀 **Getting Started**  

### **Prerequisites**  
Ensure the following tools and libraries are installed:  
- 🐍 **Python 3.8+**  
- 📷 **OpenCV**  
- 🧮 **NumPy**  
- 🎮 **Pygame**  
- 🤖 **TensorFlow 2.x** or **PyTorch 1.x**  
- 📈 **Matplotlib**  
- 🖥️ **Tkinter**

### **Installation**  
Clone the repository:  
```bash  
git clone https://github.com/yourusername/PCB_Thermal_Anomaly_Detection.git  
cd PCB_Thermal_Anomaly_Detection  

## Install the Required Dependencies  

```bash
pip install -r requirements.txt  

## 🛠️ **Usage**  

### **Prepare Your Dataset**  
- Place PCB images in the `data/images/` directory.  
- Ensure corresponding annotation files are in `data/annotations/`.  

### **Train the Model**  
```bash
python train.py --data_dir data/ --model_dir models/  

# Run the Detection Pipeline
python detect.py --model_path models/trained_model.h5  

# Launch the Pygame Interface
python main.py  

## 📊 Dataset Structure
- **data/images/**: Contains PCB images.
- **data/annotations/**: Contains annotation files in **JSON** format.

## 🧠 Model Architecture
Our model is built on a **Convolutional Neural Network (CNN)** designed to:
- Handle **high-resolution PCB images**.
- Accurately classify various **thermal anomalies**.

## 🤝 Contributing
We welcome contributions from the community! To contribute:
1. Fork the repository.
## 🤝 Contributing
We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
3. Make changes and commit:
   ```bash
   git commit -am 'Add new feature'
4. Push to the branch:
   ```bash
   git push origin feature-branch
5. Create a Pull Request.

## 📜 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## 📞 Contact
Have questions or suggestions? Reach out to us:  
**Email**: [samarthjadhav1906@gmail.com](mailto:samarthjadhav1906@gmail.com)


