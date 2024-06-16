# Smart Vision

Smart Vision is an innovative web application that provides multiple computer vision services such as PPE detection, mask detection, and more. Built using Flask and state-of-the-art computer vision algorithms, Smart Vision allows users to interact with these services through various input methods including images, videos, and real-time webcam feeds.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- **Multiple Services**: Choose from various computer vision services such as PPE detection, mask detection, etc.
- **Dedicated News Pages**: Each service comes with a dedicated news page that provides information about the service.
- **Multiple Input Methods**: Users can upload images, videos, or use a real-time webcam feed to use the services.
- **Real-Time Processing**: Leveraging computer vision algorithms for real-time analysis and results.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Database**: MongoDB
- **Computer Vision**: YOLO v5, OpenCV
- **Deployment**: Azure Virtual Machines

## Installation

To run Smart Vision locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smart-vision.git
   cd smart-vision
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up MongoDB**
   - Ensure MongoDB is installed and running on your local machine.
   - Update the MongoDB connection string in the `config.py` file.

5. **Run the application**
   ```bash
   npm start
   ```

6. **Open your browser**
   - Navigate to `http://localhost:5000` to access Smart Vision.

## Usage

1. **Home Page**
   - Browse the main page and choose from the available services.

2. **Service Selection**
   - Click on any service to learn more about it on the dedicated news page.

3. **Upload Input**
   - Choose to upload an image, video, or use the real-time webcam option.

4. **View Results**
   - View the results of the computer vision analysis in real-time.

## Project Structure

```
smart-vision/
├── app/
│   ├── static/
│   │   ├── css/
│   │   ├── img/
│   │   └── js/
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── service.html
│   └── __init__.py
├── models/
│   └── model.py
├── services/
│   ├── ppe_detection.py
│   ├── mask_detection.py
│   └── ...
├── config.py
├── requirements.txt
├── run.py
└── README.md
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Developed by [Your Name](https://github.com/yourusername)**

Feel free to contribute to this project by submitting issues or pull requests. For any queries, contact me at your.email@example.com.
