# 🗜️ Elsakr Image Compressor

> Compress images while maintaining quality. 100% local processing.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/python-3.10+-green)
![License](https://img.shields.io/badge/license-MIT-orange)

## ✨ Features

- 🖼️ **Supported Formats**: PNG, JPEG, WebP
- 📦 **Batch Compression**: Process multiple images at once
- 🎚️ **Quality Control**: Adjust compression level (1-100%)
- 📏 **Resize Option**: Set maximum width while maintaining aspect ratio
- 🔒 **100% Local**: Your images never leave your computer
- 📊 **Statistics**: See before/after sizes and savings
- 🌙 **Premium Dark UI**: Beautiful modern interface

## 📸 Screenshot

![Elsakr Image Compressor](assets/Screenshot.png)

## 🚀 Quick Start

### Option 1: Download EXE (Windows)
1. Download the latest release from [Releases](https://github.com/khalidsakrjoker/Elsakr-Image-Compressor/releases)
2. Extract the ZIP file
3. Run `Elsakr Image Compressor.exe`

### Option 2: Run from Source
```bash
# Clone the repository
git clone https://github.com/khalidsakrjoker/Elsakr-Image-Compressor.git
cd Elsakr-Image-Compressor

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
```

## 🛠️ Build EXE

```bash
pip install pyinstaller
pyinstaller --onefile --windowed --icon=assets/fav.ico --add-data "assets;assets" --name "Elsakr Image Compressor" main.py
```

## 📋 Requirements

- Python 3.10+
- Pillow >= 9.0.0

## 🎯 How It Works

1. **Add Images**: Click "Add Images" or "Add Folder"
2. **Adjust Settings**: Set quality, resize options, and output folder
3. **Compress**: Click "Compress All" and watch the magic happen
4. **Review**: Check the compression percentage for each image

## 📝 Settings

| Setting | Description |
|---------|-------------|
| Quality | 1-100%, lower = smaller file but less quality |
| Resize | Set max width, maintains aspect ratio |
| Strip EXIF | Remove metadata from images |
| Output Folder | Where to save compressed images |

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 📄 License

MIT License - feel free to use this tool for personal or commercial purposes.

## 🔗 Links

- [Elsakr Website](https://elsakr.company)
- [GitHub](https://github.com/khalidsakrjoker)
- [All Free Tools](https://elsakr.company/#free-tools)

---

Made with ❤️ by [Elsakr](https://elsakr.company)
