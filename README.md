# News-App-Api-Project
# News App with Tkinter and News API 📰

This repository contains the source code for a simple desktop News Application built using Python's Tkinter library and the News API. It allows users to browse and read the latest news headlines and articles directly from their desktop.

## Features 🚀

* 📰 Fetches news headlines and articles from the News API.
* 🖥️ User-friendly graphical interface built with Tkinter.
* 🌐 Displays news from various sources and categories.
* 🔍 Simple category selection (e.g., general, technology, sports).
* 📄 Opens full articles in your default web browser.

## Technologies Used 💻

* 🐍 Python 3
* 🎨 Tkinter (GUI library)
* 🌐 News API (for fetching news data)
* 📦 `requests` (for making HTTP requests)

## Installation 🛠️

1.  **Clone this repository:**

    ```bash
    git clone [your_repository_url]
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd [your_repository_name]
    ```

3.  **Install the required dependencies:**

    ```bash
    pip install requests
    ```

4.  **Obtain a News API key:**

    * Go to [https://newsapi.org/](https://newsapi.org/) and sign up for an account.
    * Get your API key from your dashboard.

5.  **Set your News API key:**
    * You can either insert your API key directly into the python code, or create an environment variable. For example:
        * **Environment Variable (Recommended):**
            * On Windows: `setx NEWS_API_KEY "your_api_key"`
            * On macOS/Linux: `export NEWS_API_KEY="your_api_key"`
        * **Directly in Code (Not Recommended for Public Repositories):**
            * Replace `"YOUR_API_KEY"` with your actual API key within the python file.

6.  **Run the application:**

    ```bash
    python news_app.py
    ```

    (Replace `news_app.py` with the actual name of your main Python file.)

## Usage 📝

1.  Launch the application.
2.  Select a news category from the dropdown menu.
3.  Click the "Get News" button to fetch and display headlines.
4.  Click on a headline to open the full article in your web browser.

## Contributing 🤝

Contributions are welcome! If you find any bugs or want to add new features, please feel free to open an issue or submit a pull request.

## Contact 📧

If you have any questions or feedback, you can reach me at [Your Email Address].

## Happy News Reading! 📰

**About**

This is a simple desktop News App built using Python, Tkinter, and the News API.

**Resources**

* [News API Documentation](https://newsapi.org/docs)
* [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
* [Requests Library Documentation](https://requests.readthedocs.io/en/latest/)
