# Real-Time Image Animation using Deep Learning

## Overview
This project implements real-time image animation using deep learning techniques. It takes a static image and animates it based on a driving video, leveraging models like First Order Motion Model (FOMM) or Thin-Plate Spline Motion Model (TPSMM).

## Features
- Real-time animation of images.
- Supports pre-trained deep learning models.
- Works with arbitrary driving videos.
- Easy integration with webcams and video files.
- Optimized for performance using GPU acceleration.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

### Key Dependencies:
- Python 3.7+
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- ffmpeg

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/realtime-image-animation.git
   cd realtime-image-animation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download pre-trained models (e.g., FOMM):
   ```bash
   wget https://some-url.com/pretrained-model.pth -O checkpoints/model.pth
   ```

## Usage
### Animate an Image
Run the script with an input image and driving video:
```bash
python animate.py --source-image image.jpg --driving-video video.mp4 --output output.mp4
```

### Real-time Animation with Webcam
```bash
python realtime_animate.py --source-image image.jpg
```

## Model Architecture
This project utilizes a deep learning model that learns motion representations from the driving video and transfers them onto the target image. Common architectures used:
- **First Order Motion Model (FOMM)**
- **Thin-Plate Spline Motion Model (TPSMM)**


## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

