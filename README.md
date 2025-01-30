# 🚗 Parking Detection Vision AI

## 📝 Overview
An intelligent parking detection system powered by OpenCV that automatically identifies and monitors parking space occupancy in real-time. This computer vision solution provides efficient parking space management through advanced image processing techniques.

## ✨ Key Features
- 🔍 Real-time detection of vacant and occupied parking spaces
- 🎥 Seamless video stream processing
- 🔧 Adaptable to various parking lot layouts
- 🔄 Integration capability with existing CCTV systems
- 📊 Occupancy status visualization

## 🛠️ Technical Stack
- Python
- OpenCV
- NumPy
- Video processing libraries

## 📋 Requirements
```bash
python >= 3.7
opencv-python
numpy
```

## 🚀 Quick Start
1. Clone the repository:
```bash
git clone https://github.com/yourusername/parking-detection-ai.git
cd parking-detection-ai
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the detection system:
```bash
python parking_detection.py
```

## ⚙️ Configuration

### Parking Space Definition
```python
# Define parking spaces in config.py
PARKING_SPACES = [
    {"id": 1, "coordinates": [(x1,y1), (x2,y2), (x3,y3), (x4,y4)]},
    # Add more parking spaces as needed
]
```

### Customization Parameters
Adjust these parameters in `config.py` to optimize detection for your environment:

```python
# Detection parameters
THRESHOLD_VALUE = 25
MIN_AREA = 300
MAX_AREA = 1500

# Color space parameters
HSV_LOWER = np.array([0, 0, 0])
HSV_UPPER = np.array([180, 255, 30])
```

## 🔧 System Customization
The system can be tailored to different parking environments through:

1. **Layout Adaptation**
   - Modify parking space coordinates
   - Adjust detection zones
   - Customize space numbering

2. **Detection Parameters**
   - Fine-tune threshold values
   - Adjust contour detection sensitivity
   - Modify color space ranges

3. **Integration Options**
   - Connect to existing CCTV systems
   - Configure output formats
   - Set up notification systems

## 📊 Output Examples
```
Parking Space Status:
Space #1: Occupied
Space #2: Vacant
Space #3: Occupied
Space #4: Vacant
...
```

## 🤝 Contributing
Contributions are warmly welcomed! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author
**Devakh Rashie**
