# Selina's Custom Virtual Fashion Studio

Virtual try-on is rapidly becoming the future of fashion, enabling anyone to experiment with styles, outfits, and creativity from the comfort of their own home. This project is a personal playground for exploring the power of AI-driven, multi-modal virtual try-on—where you can mix and match clothing, avatars, and backgrounds using both images and text prompts.

## About This Project

This app is built with Python, Gradio, and OpenCV, and leverages a powerful diffusion-based API for generating virtual try-on results. The backend API is accessed via RapidAPI, making it easy to connect and experiment without running heavy models locally.

- **Frontend:** Gradio (interactive web UI)
- **Backend:** Cloud API (via RapidAPI)
- **Features:**
  - Try on clothing using images or text prompts
  - Swap avatars and backgrounds
  - Experiment with creative fashion ideas

**Note:** This is a personal, non-commercial project. All API usage is subject to RapidAPI's terms and any applicable quotas.

Enjoy exploring the future of virtual fashion!

Sample of the website:
<img width="1423" alt="Screenshot 2025-05-28 at 14 29 39" src="https://github.com/user-attachments/assets/3b77d154-fb57-456c-afa5-fe87496b888a" />

## Setup and Running the App

To set up and run the app locally, follow these steps:

1. **Create a virtual environment:**
   ```zsh
   python3 -m venv venv
   ```
2. **Activate the virtual environment and install dependencies:**
   ```zsh
   source venv/bin/activate
   pip install --upgrade pip
   pip install -r requirements.txt
   ```
3. **Run the app:**
   ```zsh
   python app.py
   ```

Make sure you are in the activated virtual environment (`source venv/bin/activate`) before running the app.
