# 🖼️ Gridinator

A simple online tool to locally merge images into a beautiful grid. Upload your images, configure the layout, and download the merged result - all processed locally in your browser!

## ✨ Features

- **📤 Easy Upload**: Click to browse or drag-and-drop multiple images (JPG, PNG, GIF)
- **👀 Live Preview**: See thumbnails of your uploaded images
- **🎨 Customizable Grid**: Adjust columns, spacing, and image size
- **🤖 Intelligent Auto-sizing**: Automatically calculates optimal grid layout, or manually specify columns
- **⬇️ Download**: Export your merged grid as a high-quality PNG
- **🔒 Privacy First**: All processing happens locally in your browser - no uploads to servers
- **💻 No Installation**: Just open `index.html` in any modern web browser

## 🚀 Usage

1. Open `index.html` in your web browser
2. Upload images by clicking the upload area or dragging and dropping files
3. Configure your grid layout using the controls:
   - **Columns**: Leave blank or type "Auto" for intelligent sizing, or specify a number (1-10) for manual control
   - **Spacing**: Adjust the gap between images (0-50px)
   - **Image Size**: Select from Small, Medium, Large, or Extra Large
4. Click "Generate Grid" to create your merged image
5. Click "Download Grid" to save the result

### Auto Grid Sizing

By default, Gridinator intelligently calculates the optimal grid layout:
- **1-4 images**: Creates compact layouts (1x1, 2x1, 3x1, 2x2)
- **5+ images**: Calculates a balanced grid that's close to square, with a slight preference for landscape orientation
- **Manual override**: Simply type a number in the Columns field to specify your own layout

## 🛠️ Technical Details

- **Single File**: Complete application in one HTML file
- **No Dependencies**: Pure HTML5, CSS3, and vanilla JavaScript
- **Modern**: Uses HTML5 Canvas API for image processing
- **Responsive**: Works on desktop and mobile devices
- **Offline Ready**: Works without internet connection after initial load

## 📸 Screenshots

![Gridinator Interface](https://github.com/user-attachments/assets/c46bf1ae-1999-4672-8761-2d60e9c87ee8)

## 🤝 Contributing

Feel free to open issues or submit pull requests!

## 📄 License

Open source - feel free to use and modify!
