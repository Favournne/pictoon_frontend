 ( Updates will be made and pushed subsequently as this project is still in development )
🌟 Pictoon Frontend


Pictoon is a sleek, mobile-first frontend for an AI-powered image transformation web app. It allows users to upload images and convert them into cartoon-style or animated visuals using integrated third-party services.

🚀 Features

 🎨 Upload any image to transform it into a cartoon or animated style
 🖼 Clean, responsive design using HTML, CSS, and Bootstrap
 📱 Mobile-first UI with seamless transitions between pages:

Landing Page
Body page
Upload Page

 
🔗 Connects to a Django backend that handles image processing with third-party AI services

 📁 Project Structure

cartoonweb
├── index.html            # Landing page
├── upload.html           # Image upload interface
├── body.html           #homepage
├── css/
│   └── style.css         # Custom white & purple theme styling
├── js/
│   └── main.js           # Handles image preview, interactions (optional)
├── images/           # Icons, logos, and placeholders

🛠 Tech Stack

HTML5
CSS3
Bootstrap 5
JavaScript (vanilla)
Optionally integrates with:

  Firebase Auth (frontend)
  Django REST API (backend)

 🧪 How to Use

1. Clone this repository:

   ```
   bash
   git clone https://github.com/your-username/pictoon-frontend.git
   cd pictoon-frontend
   ```

2. Open the `index.html` file in your browser or serve using a local server:

   ```bash
   # If you have Python installed
   python -m http.server
   ```

3. Upload your image via the Upload Page and preview results from the backend.

---

🔌 Backend Integration

Make sure the Django backend is running and exposed via an API endpoint (e.g. `/api/convert-image/`).

Update the JavaScript `fetch()` or form `action` methods to point to the correct backend URL.

 🎯 TODOs

[ ] Add loader/spinner for processing
[ ] Handle errors on failed uploads
[ ] Add user authentication via Firebase
[ ] Enable download button after conversion

 🧑‍💻 Contributing

Pull requests are welcome. Feel free to open an issue if you find bugs or have feature suggestions.

 📄 License

MIT License © 2025 Favour Ezemonye


