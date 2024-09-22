# Web Scraping with Python Selenium

## Prerequisites

Ensure that you have Python installed on your system. If not, follow the instructions below.

## Installing Python

1. **Download Python:**
   - Visit the official Python website: [python.org/downloads](https://www.python.org/downloads).
   - Download the latest version of Python for your operating system.

2. **Run the Installer:**
   - Double-click the downloaded `.exe` file to start the installation.
   - Check the box labeled **"Add Python to PATH"** before clicking "Install Now."

3. **Verify Installation:**
   - Open **Command Prompt** (Windows) or **Terminal** (macOS/Linux).
   - Type `python --version` and press Enter. This should display the installed Python version if everything is set up correctly.


## Installing Selenium
1. **Create a Virtual Environment:**
   - In the terminal, navigate to the project directory and run the following command to create a virtual environment:

     ```sh
     python -m venv .env
     ```

2. **Activate the Virtual Environment:**
   - **Windows:** Run:

     ```sh
     .\.env\Scripts\activate
     ```
   - **macOS/Linux:** Run:

     ```sh
     source .env/bin/activate
     ```

3. **Install Selenium:**
   - Once the virtual environment is activated, install Selenium using `pip`:

     ```sh
     pip install selenium
     ```

## Running the Python Script

1. **Navigate to the `src` Folder:**
   - Open the `src` folder within your project directory.

2. **Set the Last Page Number:**
   - Edit the `requirements.txt` file and specify the last page number for scraping.

3. **Open Command Prompt/Terminal in the `src` Folder:**
   - Open a terminal session and navigate to the `src` folder. Ensure your virtual environment is activated.

4. **Run the Python Script:**
   - Run the following command to execute the script:

     ```sh
     python main.py
     ```

