# News App using Tkinter

This Python script creates a simple graphical news application using Tkinter, displaying top headlines based on selected country and category fetched from the News API.



## Features

- Selection of Country and Category: Users can choose a country and a news category (e.g., Business, Entertainment, Technology) from dropdown menus.
- Search Functionality: Users can perform searches based on keywords to filter news articles.
- Dynamic Display: The application dynamically displays fetched news headlines in a scrollable frame with scrollbar support.
- Error Handling: In case of errors during data retrieval, appropriate error messages are displayed to the user.

## Usage

1. Ensure you have an active internet connection.
2. Run the Python script `newsApp_v2.py` or `newsApp.py`.
3. Select a country, category, and optionally enter a search keyword.
4. Click the refresh button or press Enter to load the news data.
5. View the fetched news headlines displayed in the interface.

## Requirements

- Python 3.x
- Tkinter (usually included with Python installation)
- `urllib` library (for handling URL requests)
- `json` library (for JSON data handling)
- `threading` module (for multithreading)
- `tkinter.ttk` module (for themed Tkinter widgets)


## Steps to Install and Run

1. **Clone or Download the Repository:**
- Clone the repository using Git:
```bash
git clone https://github.com/xenon134/Nova
```
- Alternatively, you can download the repository as a ZIP file and extract it to a preferred location on your computer.

2. **Navigate to the Project Directory:**

Open a terminal or command prompt and change directory to the location whereyou've cloned or extracted the repository.
```bash
cd Nova
```

Run the Python script newsApp_v2.py or newsApp.py:

```bash
python newsApp_v2.py 
```
or
```bash
python newsApp.py 
```