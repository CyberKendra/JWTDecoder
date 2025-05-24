# 🔐 JWT Decoder

A modern, secure, and visually stunning JWT (JSON Web Token) decoder built with vanilla HTML, CSS, and JavaScript. Features a cyberpunk-inspired design with neon glowing effects and complete client-side processing for maximum security.

[**🔗 Live Demo**](https://www.cyberkendra.com/p/jwt-decoder.html)

## ✨ Features

- **🎨 Modern UI Design**: Beautiful neon-themed interface with glowing effects
- **🔒 Client-Side Processing**: All decoding happens in your browser - no data sent to servers
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **🔍 Clear Token Structure**: Separate sections for Header, Payload, and Signature
- **⚡ Real-Time Decoding**: Instant JWT parsing and validation
- **🎯 Error Handling**: Clear feedback for invalid tokens
- **🌐 Zero Dependencies**: Pure HTML, CSS, and JavaScript - no external libraries

## 🚀 Demo

![JWT Decoder Preview](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgpq12QGn8T_kdovlF59MvJsChxUZ9oJn7GRDTX0A9OacQRlwA3AZ3Qux8bZj_uCTXWn3-sI0vAaHx_4Ah5m0ojwuQ9zVqQ_YIc5P2wWuF9-rzt0IPzGUMy6KONUHcUEkjZgCAjs0bmKJN5Fqb1Sdhm9gczrQ2ta7ImZ2lQIZhjQiRdwNXUndjOrHbIUk8/s1600/jwt-decode.jpeg)

[**🔗 Live Demo**](https://www.cyberkendra.com/p/jwt-decoder.html)

## 🛠️ Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start decoding JWT tokens immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/your-username/jwt-decoder.git
cd jwt-decoder
```

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages to host your own version.

## 📖 Usage

1. **Paste Your JWT**: Copy any JWT token into the input textarea
2. **Click Decode**: Hit the glowing "Decode" button
3. **View Results**: See the decoded Header, Payload, and Signature in separate sections

### Example JWT Token
```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c
```

## 🎨 Design Features

- **Neon Glow Effects**: Beautiful cyan/teal glowing borders and shadows
- **Cyberpunk Aesthetic**: Dark theme with bright accent colors
- **Material Design Elements**: Clean, modern component styling
- **Smooth Animations**: Hover effects and transitions for better UX
- **Typography**: Monospace fonts for code readability

## 🔧 Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with flexbox, animations, and effects
- **Vanilla JavaScript**: Pure JS for JWT decoding logic
- **Google Fonts**: Roboto and Share Tech Mono typography

### Browser Support
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

### Security Features
- **No Server Communication**: All processing happens locally
- **No Data Storage**: Tokens are never stored or cached
- **Privacy Focused**: Your JWTs never leave your device

## 🔍 How JWT Decoding Works

This tool performs the following steps:

1. **Token Validation**: Checks if the input follows JWT format (header.payload.signature)
2. **Base64 Decoding**: Decodes the header and payload using `atob()`
3. **JSON Parsing**: Converts decoded strings to readable JSON objects
4. **Display**: Shows each component in a formatted, readable way

## 🚨 Security Notice

**⚠️ Important**: While this tool processes tokens client-side, always be cautious when handling JWTs containing sensitive information. Never share your tokens publicly or use them in untrusted environments.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit Your Changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Ideas for Contributions
- [ ] JWT signing functionality
- [ ] Multiple algorithm support display
- [ ] Token expiration warnings
- [ ] Copy to clipboard buttons
- [ ] Dark mode toggle
- [ ] More theme options
- [ ] QR code generation for tokens


## 👨‍💻 Author

**Your Name**
- X: [@cyberkendra](https://twitter.com/cyberkendra)
- Facebook: [Cyber Kendra](https://fb.com/cyberkendra)
- Twitter: [@your-twitter](https://twitter.com/your-twitter)

## 🙏 Acknowledgments

- Inspired by [jwt.io](https://jwt.io) - the original JWT debugger
- Design inspiration from cyberpunk and Material Design aesthetics
- Google Fonts for typography
- The JWT community for token standards

---

⭐ **If you found this project helpful, please give it a star!** ⭐
