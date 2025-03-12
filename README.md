# facerecognition
 Installation

Clone the repository:

git clone https://github.com/yourusername/face-recognition.git
cd face-recognition

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

📋 Usage

Add known faces:

python add_faces.py --name "Your Name" --image "path/to/image.jpg"

Run face recognition:

python recognize_faces.py --source webcam  # Or use --source "path/to/video.mp4"

(Optional) Run tests:

pytest

📁 Project Structure

face-recognition/
├── data/
│   ├── known_faces/
│   └── unknown_faces/
├── add_faces.py
├── recognize_faces.py
├── requirements.txt
└── README.md

⚙️ Requirements

Python 3.8+

OpenCV

dlib

face_recognition

numpy

Install them with:

pip install opencv-python dlib face-recognition numpy

📖 References

face_recognition library

OpenCV documentation

🤝 Contributing

Fork the project.

Create a feature branch:

git checkout -b feature/your-feature

Commit changes and push:

git commit -m "Add new feature"
git push origin feature/your-feature

Create a pull request.

📧 Contact

For any inquiries, contact your aniketspawar3031@gmail.com.

📝 License

This project is licensed under the MIT License.

