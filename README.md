# 🚀 AI Promotional Image Generator

## 🌈 Project Vision

This cutting-edge AI application revolutionizes product marketing by transforming ordinary product images into stunning, professionally designed promotional materials. By harnessing the power of advanced AI technologies like Google's Gemini and state-of-the-art diffusion models, the tool automates the creative process of generating eye-catching promotional content.

## 🌟 Comprehensive Features

### 1. Intelligent Promotional Text Generation
- **AI-Powered Analysis**: Leverages Google's Gemini AI to deeply analyze product images
- **Context-Aware Writing**: Generates contextually relevant and compelling promotional text
- **Customizable Prompts**: Flexible text generation instructions to match your brand voice
- **Multi-Style Text Creation**: Adapts to different marketing tones and styles

### 2. Dynamic Promotional Image Layouts
- **Three Unique Layouts**:
  - Center-aligned presentation
  - Sleek left-aligned design
  - Elegant right-aligned composition
- **Smart Image Processing**:
  - Automatic image resizing
  - Intelligent text positioning
  - Preservation of image aspect ratio
- **Visual Consistency**: Maintains professional design standards

### 3. Advanced Background Generation
- **AI-Driven Background Creation**:
  - Utilizes cutting-edge diffusion models
  - Generates contextually appropriate backgrounds
- **Flexible Configuration**:
  - Multiple background output options
  - Customizable generation parameters
  - Control over inference steps and randomness
- **Quality Assurance**: 
  - Supports negative prompting
  - Implements advanced image processing techniques

## 🛠 Tech Stack

### Primary Technologies
- **Programming Language**: Python 3.8+
- **Web Interface**: Gradio
- **AI Engines**:
  - Google Gemini API
  - Hugging Face Diffusion Models
- **Machine Learning**: 
  - PyTorch
  - Transformers
- **Image Processing**: 
  - PIL (Python Imaging Library)
  - Transparent Background Removal

### Technical Highlights
- GPU-Accelerated Processing
- Memory-Efficient Model Loading
- Cross-Platform Compatibility
- Scalable Architecture

## 📋 System Requirements

### Hardware
- **Recommended**: 
  - CUDA-Compatible GPU
  - Minimum 16GB RAM
  - At least 50GB Free Storage
- **Minimum**:
  - CPU with AVX2 Support
  - 8GB RAM
  - 25GB Free Storage

### Software Prerequisites
- Python 3.8 or higher
- CUDA Toolkit (for GPU acceleration)
- pip package manager

## 🔧 Comprehensive Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/yaseen2444/ai-promo-generator.git
cd ai-promo-generator
```

### 2. Create Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -f https://download.pytorch.org/whl/cu116 \
    torch \
    torchvision

pip install -r requirements.txt
```

### 4. Configuration Steps
- Obtain Google Gemini API Key
- Configure `.env` file with API credentials
- Set up GPU/CUDA settings if applicable

## 📦 Detailed `requirements.txt`
```
# AI and Machine Learning
torch
torchvision
numpy
transformers
git+https://github.com/huggingface/diffusers

# Image Processing
Pillow
transparent-background

# Web Interface
gradio
google-generativeai

# Optional GPU Acceleration
xformers  # Recommended for CUDA
```

## 🚀 Execution Modes

### Standard Execution
```bash
python app.py
```

### GPU-Optimized Mode
```bash
CUDA_VISIBLE_DEVICES=0 python app.py  # Specify GPU
```

## 🎛 Advanced Customization

### Prompt Engineering
- Fine-tune text generation prompts
- Adjust generation temperature
- Control text complexity and style

### Background Generation Parameters
- Custom background descriptions
- Control output quantity
- Adjust inference complexity
- Set reproducible random seeds

## 🌐 Potential Applications

- E-commerce Product Marketing
- Social Media Content Creation
- Digital Advertising Campaigns
- Brand Storytelling
- Personal Portfolio Enhancement
- Real Estate Listing Presentations
- Event and Promotional Material Design

## 🤝 Contribution Guidelines

### How to Contribute
1. Fork the Repository
2. Create Feature Branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit Changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to Branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open Pull Request

### Development Roadmap
- [ ] Multi-language Support
- [ ] Enhanced Background Style Options
- [ ] Real-time Preview Functionality
- [ ] Cloud Deployment Scripts

## 📄 Licensing

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- Google AI Team
- Hugging Face Community
- PyTorch Developers
- Open-Source Contributors

## 📞 Support and Community

- 📧 Email: yaseenmohammadap37@gmail.com
---

**Disclaimer**: This tool is designed to enhance creative processes and should be used responsibly and ethically in marketing practices.
