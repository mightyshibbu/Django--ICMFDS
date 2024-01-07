# ICMFDS (Image Content-based Image Forgery Detection System)

ICMFDS is a Django-based project designed for Image Forgery Detection System using Python's Hash Library. The project detects image forgery by utilizing the MD5 hashing function to analyze image patterns. It stores the hash values in databases for future reference and comparison.

## Objective

The primary objective of the ICMFDS project is to detect image forgeries based on their content. It achieves this by generating hash values using Python's MD5 function, allowing the system to identify and compare patterns within images for potential alterations or forgeries.

## Key Features

- Image Forgery Detection: Detects potential image forgeries by analyzing the content-based hash values of images.
- MD5 Hash Function: Utilizes Python's MD5 hashing algorithm to generate unique hashes for image patterns.
- Database Storage: Stores computed hash values in databases for future comparison and analysis.

## Installation and Setup

1. **Clone the Repository:**
    ```bash
    $ git clone <repository-url>
    $ cd icmfds-django
    ```

2. **Install Dependencies:**
    ```bash
    $ pip install -r requirements.txt
    ```

3. **Run the Django Application:**
    ```bash
    $ python manage.py runserver
    ```

4. **Access the Application:**
    - Open a web browser and go to `http://localhost:8000` to access the ICMFDS application.

## Usage

1. **Upload Images:**
    - Use the provided interface to upload images for forgery detection.

2. **Forgery Detection:**
    - The system automatically computes and stores MD5 hash values for uploaded images.
    - Detects potential forgeries by comparing hash values and identifying discrepancies.

3. **Results and Analysis:**
    - View results and analysis of detected image forgeries within the application.

## Contributing

Contributions to the ICMFDS project are welcome! Feel free to fork the repository, make improvements, and create pull requests.
