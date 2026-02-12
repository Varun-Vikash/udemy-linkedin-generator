# 📜 Certificate Generator - Udemy & LinkedIn Learning

A web-based application that allows you to generate realistic-looking course completion certificates for **Udemy** and **LinkedIn Learning** platforms. This project is built using pure HTML, CSS, and JavaScript with no backend dependencies.

> ⚠️ **DISCLAIMER**: This tool is created for **educational and entertainment purposes only**. These certificates are not official and should **NOT** be used for professional purposes, job applications, or any fraudulent activities.

---

## ✨ Features

- 🎓 **Dual Platform Support**: Generate certificates for both Udemy and LinkedIn Learning
- 📝 **Customizable Fields**: 
  - First Name & Last Name
  - Course Name
  - Completion Date
  - Course Length/Duration
  - Instructor Name (Udemy only)
- 🎨 **Authentic Design**: Mimics the official certificate design of both platforms
- 📥 **PDF Export**: Download generated certificates as high-quality PDF files
- 🎯 **No Backend Required**: Completely client-side application
- 📱 **Desktop Optimized**: Best viewed on desktop or laptop devices
- 🔢 **Random Certificate IDs**: Generates unique-looking certificate numbers and reference IDs

---

## 🚀 Demo

### How It Works

1. **Landing Page**: Choose between Udemy or LinkedIn Learning certificate generator
2. **Form Input**: Fill in your details (name, course, date, duration, etc.)
3. **Generate**: Click the generate button to create your certificate
4. **Download**: Save the certificate as a PDF to your device

---

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and layout
- **JavaScript (Vanilla)**: Logic and interactivity
- **Bootstrap 5**: UI components and responsive design (landing page)
- **html2pdf.js**: PDF generation functionality
- **Google Fonts**: Custom typography (Montserrat, Poppins, Open Sans, Lato)

---

## 📦 Installation & Usage

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for better experience)

### Running Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Varun-Vikash/udemy-linkedin-generator.git
   cd udemy-linkedin-generator
   ```

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

3. **Navigate to the application**
   - Open `http://localhost:8000` (if using a local server)
   - Or directly open `index.html` in your browser

4. **Generate Certificates**
   - Select a platform (Udemy or LinkedIn Learning)
   - Fill in the required information
   - Click "Generate" to create your certificate
   - Click "Download PDF" to save it

---

## 📁 Project Structure

```
udemy-linkedin-generator/
│
├── index.html              # Landing page with platform selection
├── udemy.html             # Udemy certificate generator page
├── linkedin.html          # LinkedIn Learning certificate generator page
├── README.md              # Project documentation
│
├── css/
│   ├── style.css          # Landing page styles
│   ├── udemy.css          # Udemy certificate styles
│   └── linkedin.css       # LinkedIn certificate styles
│
├── js/
│   ├── udemy.js           # Udemy certificate logic
│   └── linkedin.js        # LinkedIn certificate logic
│
├── img/                   # Images and assets
│   ├── udemy-logo.png
│   ├── Learning.png
│   ├── LinkedIn left-2.png
│   ├── Sign2.JPG
│   ├── icon.png
│   └── BG.mp4             # Background video for landing page
│
└── font/                  # Custom fonts (if any)
```

---

## ⚠️ Important Notes

1. **Educational Purpose Only**: This project is created for learning and fun. Do not use these certificates for:
   - Job applications
   - Resume building
   - Professional portfolios
   - Any form of credential fraud

2. **Not Affiliated**: This project is not affiliated with, endorsed by, or connected to Udemy Inc. or LinkedIn Corporation.

3. **Desktop Recommended**: For the best experience, use this application on a desktop or laptop computer. Mobile devices will show a warning message.

4. **Certificate Validity**: These certificates are NOT valid and hold no official recognition from Udemy or LinkedIn.

---

## 🎯 Features in Detail

### Udemy Certificate Generator
- Generates certificate number in format: `UC-XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX`
- Includes certificate URL: `ude.my/UC-...`
- Adds reference number
- Supports multiple instructors (separated by commas)
- Multi-line course names supported

### LinkedIn Learning Certificate Generator
- Generates certificate ID in format: `AUXXIXXAXXRPEUO_IEXXRXXLXXACXXSN`
- Includes official LinkedIn Learning branding
- Shows VP signature
- Displays company address
- Professional layout with decorative borders

---

## 🔮 Future Improvements

Potential enhancements that could be added:

- [ ] Mobile responsive design
- [ ] Additional platforms (Coursera, edX, etc.)
- [ ] More customization options (colors, fonts)
- [ ] Certificate templates selection
- [ ] Image upload for profile picture
- [ ] Multiple language support
- [ ] Certificate verification URL generation
- [ ] Dark mode support
- [ ] Share on social media functionality

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

Please ensure your code follows the existing style and structure.

---

## 📄 License

This project is open source and available for educational purposes. Please use responsibly and ethically.

---

## 👨‍💻 Author

**Varun Vikash**

- GitHub: [@Varun-Vikash](https://github.com/Varun-Vikash)
- Repository: [udemy-linkedin-generator](https://github.com/Varun-Vikash/udemy-linkedin-generator)

---

## 🙏 Acknowledgments

- Certificate designs inspired by official Udemy and LinkedIn Learning platforms
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) for PDF generation
- [Bootstrap](https://getbootstrap.com/) for UI components
- [Google Fonts](https://fonts.google.com/) for typography

---

## ⚖️ Legal Disclaimer

This project is created solely for educational and demonstration purposes. The developers and contributors are not responsible for any misuse of this tool. Using fake certificates for professional purposes may constitute fraud and can have legal consequences. Always be honest about your qualifications and achievements.

**USE AT YOUR OWN RISK**

---

<div align="center">

**If you find this project useful, please consider giving it a ⭐ on GitHub!**

Made with ❤️ for learning purposes

</div>