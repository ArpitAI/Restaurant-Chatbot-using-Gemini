# 🥄 The Golden Spoon Chatbot 🍽️

-----

## ✨ Overview

Welcome to **The Golden Spoon Chatbot**\! This intelligent Streamlit application serves as your virtual assistant for "The Golden Spoon" restaurant, located at 123 Main Street in Varanasi, Uttar Pradesh. Powered by **Google's Gemini Pro AI**, this chatbot provides instant answers to frequently asked questions about our diverse menu (Indian, Chinese, Korean, and more\!), services (delivery, reservations, catering), and general restaurant information.

-----

## 🌟 Features

  * **Diverse Menu Information:** Get details on a wide range of dishes, including authentic Indian, Chinese, Korean, Continental, South Indian, Italian, Mexican, American, and Australian cuisines.
  * **Vegan & Vegetarian Options:** Easily discover our extensive selection of plant-based and vegetarian dishes.
  * **Mushroom Specialties:** Find our delicious mushroom-based offerings.
  * **Street Food & Chaat:** Explore our popular Indian street food and chaat varieties.
  * **Restaurant Details:** Inquire about our location, contact numbers, operating hours, and accessibility.
  * **Service Information:** Understand our home delivery policy, reservation process, catering services, and special offers.
  * **Interactive Q\&A:** Ask questions in natural language and receive comprehensive answers.
  * **User-Friendly Interface:** Built with Streamlit for a simple and intuitive chat experience.

-----

## 🚀 How to Run Locally

Follow these steps to get The Golden Spoon Chatbot up and running on your local machine:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

    *(Remember to replace `your-username/your-repo-name.git` with your actual GitHub repository URL.)*

2.  **Create a virtual environment:**

    ```bash
    python -m venv venv
    ```

3.  **Activate the virtual environment:**

      * **Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
      * **macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5.  **Set up environment variables:**

      * Create a file named `.env` in the root directory of your project.
      * Add your Google Gemini API key to this file:
        ```
        GOOGLE_API_KEY="YOUR_GEMINI_API_KEY"
        ```
        You can obtain a Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

6.  **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

    This will open the chatbot in your web browser.

-----

## ⚙️ Project Structure

```
├── .env                  # Environment variables (IGNORED by Git)
├── .gitignore            # Specifies intentionally untracked files to ignore
├── app.py                # Main Streamlit application file
├── requirements.txt      # List of Python dependencies
└── README.md             # This file!
```

-----

## 🤝 Contributing

We welcome contributions\! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1.  Fork this repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add new feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

-----

## 📝 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

-----

## 🙏 Acknowledgements

  * Powered by [Google Gemini Pro](https://ai.google.dev/models/gemini).
  * Built with [Streamlit](https://streamlit.io/).

-----
