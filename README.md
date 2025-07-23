# Audio Modifier Web Tool

![Audio Modifier Screenshot](https://placehold.co/800x450/1f2937/e5e7eb?text=Add+a+Screenshot+of+Your+App+Here)

A simple, browser-based tool for creatively transforming audio files. This application allows users to upload an audio track and apply various real-time effects, perfect for producers, content creators, and anyone looking to experiment with sound. The goal is to provide an intuitive interface for altering audio characteristics, which can help in creating unique, royalty-free-like sounds from existing tracks.

**Live Demo:** [Link to your live GitHub Pages site here]

---

## ✨ Features

- **Dark Theme UI:** A sleek, modern interface that's easy on the eyes.
- **File Upload:** Supports drag-and-drop or standard file selection for all common audio formats (MP3, WAV, OGG, etc.).
- **Speed & Tone Control:** Adjust the playback speed, which also affects the pitch and tone of the audio. Go from slow and deep to fast and high-pitched.
- **Reverb:** Add spaciousness to your sound with an adjustable dry/wet reverb control.
- **Fluctuation (Tremolo):** Create rhythmic volume modulation with a variable-speed tremolo effect.
- **One-Click Lofi Effect:** Instantly apply a curated lofi sound, complete with:
    - A low-pass filter for a warm, muffled feel.
    - Subtle saturation for character.
    - Gentle pitch wobble (vibrato) for a vintage tape effect.
    - Procedurally generated vinyl crackle noise.
- **Real-Time Preview:** Hear your changes instantly as you adjust the controls.
- **Download Modified Audio:** Process and export your creation as a high-quality `.wav` file.

---

## 🛠️ Tech Stack

This project is built entirely with front-end technologies, running completely in the user's browser. No server-side processing is required.

- **HTML5:** For the core structure of the application.
- **Tailwind CSS:** For a utility-first approach to styling and creating the responsive, modern UI.
- **JavaScript (ES6+):** For all the application logic, event handling, and DOM manipulation.
- **Web Audio API:** The core technology used for all audio processing, including decoding, applying effects (Filters, Gain, Convolvers, Oscillators), and rendering the final output.

---

## 🚀 How to Use

1.  **Upload an Audio File:** Drag and drop an audio file onto the designated area, or click to select a file from your computer.
2.  **Adjust the Effects:**
    - Use the **sliders** to control the Speed, Reverb, and Fluctuation.
    - Flip the **Lofi Effect** switch to toggle the lofi preset on or off.
3.  **Preview Your Sound:** Click the **Play** button to listen to the modified audio in real-time.
4.  **Download Your Creation:** Once you're happy with the result, click the **Download Modified Audio** button to save the file to your computer.

---

## 💻 Running Locally

To run this project on your local machine:

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```
3.  **Open the `index.html` file:**
    - Simply open the `index.html` file in your web browser of choice (like Chrome, Firefox, or Edge).
    - For the best experience and to avoid potential local file access issues, it's recommended to use a simple live server extension (like "Live Server" for VS Code).

---

## ⚖️ Disclaimer

This tool is provided for creative and experimental purposes. Users are solely responsible for ensuring that their use of the output audio complies with all applicable copyright laws and regulations. The creators of this tool are not liable for any copyright infringement.

---
