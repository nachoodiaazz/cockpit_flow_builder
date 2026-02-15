# Cockpit Flow Builder

A free, open-source web application for student pilots to create interactive cockpit checklist flows with visual annotations.

## 🎯 Features

### Image Management (Position Mode)
- **Import multiple cockpit images** per flow
- **Drag to reposition** images on canvas
- **Resize** images using corner handles
- **Crop** images with visual selection tool
- **Zoom & pan** for precise positioning

### Flow Annotation (Annotate Mode)
- **PF/PM roles** with customizable colors
- **Click to add numbered steps** on cockpit images
- **Adjustable curve paths** - drag control points to route lines around important elements
- **Edit step descriptions** inline
- **Undo/redo** support (Ctrl+Z / Ctrl+Y)

### Professional Exports
- **PDF Export** - Beautiful two-column layout with image on first page, PF/PM steps side-by-side
- **PNG Export** - High-resolution annotated cockpit image
- **Text Export** - Plain text step lists
- **LaTeX Export** - Ready for Overleaf integration

### Templates & Storage
- **Save flows as templates** for reuse
- **Browser storage** - your work persists between sessions
- **No server required** - everything runs locally

## 🚀 How to Use

### Quick Start
1. **Download** the `cockpit-flow-builder.html` file
2. **Open it** in any modern web browser (Chrome, Firefox, Safari, Edge)
3. **Start creating** - no installation or account needed!

### Basic Workflow
1. **Add images** of your cockpit panels
2. **Position & resize** images to build your full cockpit layout
3. **Crop** if needed to remove unwanted areas
4. **Confirm positions** when ready
5. **Switch to Annotate Mode**
6. **Select PF or PM** role
7. **Click on the cockpit** to add numbered steps
8. **Drag curve control points** to adjust flow line paths
9. **Edit step names** by clicking on them in the sidebar
10. **Export as PDF** for a professional checklist document

## 🎨 Screenshots

### Position Mode
Drag, resize, and crop cockpit images to build your layout.

### Annotate Mode
Add PF/PM steps with color-coded numbering and adjustable curves.

### PDF Export
Professional two-column layout with visual flow and step lists.

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Undo | `Ctrl + Z` |
| Redo | `Ctrl + Y` or `Ctrl + Shift + Z` |
| Delete selected step | `Delete` |
| Pan view | `Shift + Drag` or `Right Click + Drag` |
| Zoom | `Mouse Wheel` |

## 🛠️ Technical Details

- **Single HTML file** - no build process required
- **Client-side only** - no server, no database
- **Privacy-focused** - all data stays in your browser
- **Open source libraries**: React, jsPDF
- **Works offline** after first load

## 🤝 Contributing

This is a single-file application. To contribute:
1. Download the HTML file
2. Make your changes
3. Test in a browser
4. Submit a pull request

## 📄 License

MIT License - free for personal and commercial use.

## 🙏 Credits

Built with:
- [React](https://reactjs.org/) - UI framework
- [jsPDF](https://github.com/parallax/jsPDF) - PDF generation
- No external APIs or tracking

## 💡 Tips

- **Save templates** for different aircraft types
- **Errors** press "cancel crop" if changes have not been made when editing images
- **Use high-quality images** for best PDF output
- **Adjust curve control points** to avoid hiding important switches/gauges
- **Zoom in** for precise step placement
- **Name your steps clearly** for better checklists



**Made for pilots, by pilots** ✈️

https://github.com/YOUR-USERNAME/cockpit-flow-builder
