# File Sharing Application

## Description

File Sharing Application is a beginner-level Computer Networks project developed using Python and Flask.

It allows users to upload, view, and download files between devices connected to the same Wi-Fi network.

## Features

- Upload files from a computer.
- View uploaded files.
- Download files.
- Share files between devices on the same Wi-Fi network.
- Simple web-based interface.

## Technologies Used

- Python
- Flask
- HTML
- CSS
- HTTP Networking

## Project Structure

```text
FileSharing/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── uploads/
│   └── .gitkeep
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/File-Sharing-Application.git
```

### Step 2: Open the Project Folder

```bash
cd File-Sharing-Application
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 4: Activate the Virtual Environment

```powershell
venv\Scripts\Activate
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Run the Application

```bash
python app.py
```

### Step 7: Open in Browser

http://127.0.0.1:5007

## How It Works

1. Open the application in a browser.
2. Select a file from your computer.
3. Click the Upload File button.
4. The file is saved in the uploads folder.
5. The uploaded file appears in the available files list.
6. Other devices connected to the same Wi-Fi can access and download the file using the computer's local IP address.

## Learning Outcomes

- Understand Local Area Networks.
- Learn client-server communication.
- Understand HTTP file transfer.
- Learn file handling in Python.
- Develop a web application using Flask.

## Future Enhancements

- Add user authentication.
- Add file size restrictions.
- Add file deletion functionality.
- Display file sizes.
- Add upload progress information.

## Disclaimer

This project is developed for educational purposes. Use it only on trusted networks and share files only with authorized users.

## Author

Computer Science and Engineering Student
