# PyLocate


This website is a **PyLocate** application that allows users to explore details of various locations. It's designed to take a given initial location (by default, **RCOEM**) and identify nearby places based on specified categories.

---

## Project Explanation

This Python project serves as a geographical **PyLocate**. It leverages various Python libraries to process geographical data, calculate distances, and visually present nearby locations on an interactive map.

Here's a breakdown of its core functionality:

* **Initial Location**: The application starts with a predefined initial location (RCOEM).
* **Category-Based Search**: Users can select different categories to find nearby locations relevant to their interests.
* **Distance Calculation**: It accurately calculates distances between the initial location and potential nearby points.
* **Interactive Map Display**: All identified locations are displayed on an interactive map, providing a clear visual representation.

---

## Key Components & Libraries

The project relies on a set of powerful Python libraries to deliver its features:

### 1. Imports

The project imports essential libraries for data manipulation, geographical calculations, and interactive visualization:

* `pandas`: For efficient data handling and analysis.
* `geopy`: Specifically `geodesic` for precise distance calculations between geographical coordinates.
* `ipyleaflet`: To create and display interactive maps within Jupyter Notebook.
* `ipywidgets`: For building interactive user interface elements like dropdown lists and buttons.
* `IPython.display`: To enable custom HTML styling and content display within the Jupyter environment.

### 2. Custom CSS Styling

The project incorporates custom CSS styles to enhance the appearance and user experience of the interactive widgets used throughout the application.

### 3. Libraries and Datasets Used

Here's a detailed list of the primary libraries utilized in the code:

* **Pandas (`import pandas as pd`)**
    * A fundamental library for data manipulation and analysis in Python. It's crucial for managing location data and other tabular information.

* **Geopy (`from geopy.distance import geodesic`)**
    * This library specializes in geocoding (converting addresses to geographical coordinates) and, importantly for this project, calculating precise geodesic distances between two sets of coordinates.

* **ipyleaflet (`from ipyleaflet import Map, Marker`)**
    * An interactive mapping library specifically designed for Jupyter Notebooks. It enables the creation of dynamic maps with markers to pinpoint locations.

* **ipywidgets (`import ipywidgets as widgets`)**
    * Provides interactive HTML widgets for Jupyter Notebooks. In this project, it's used to create user-friendly interactive elements such as dropdown menus (`widgets.Dropdown`) and buttons (`widgets.Button`) for seamless user interaction.

* **IPython.display (`from IPython.display import display, HTML`)**
    * Offers functionalities to create and render HTML content directly within IPython environments. This is particularly useful for applying custom styling and customizing the display of various elements within Jupyter Notebooks.

---

## How to Use (Assumptions)

1.  **Clone the Repository:**
    ```bash
    git clone <your-repo-url>
    cd <your-repo-name>
    ```
2.  **Install Dependencies:**
    It's recommended to use a virtual environment.
    ```bash
    pip install pandas geopy ipyleaflet ipywidgets
    ```
3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Open the relevant `.ipynb` file (e.g., `location_finder.ipynb`) in your browser.
4.  **Interact with the Widgets:**
    Once the notebook is running, you'll be able to use the dropdown lists and buttons to select locations and categories, and view the results on the interactive map.

---

Feel free to contribute to this project or suggest improvements!
