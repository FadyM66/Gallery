# Gallery

## Setup Instructions

# 1. Create Project Directory
```bash
mkdir Gallery
cd Gallery
```

# 2. Create and Activate a Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate
```

# 3. Clone the Repository
```bash
git clone https://github.com/FadyM66/Gallery.git
cd Gallery
```
# 4. Update and Upgrade the System
```bash
sudo apt update
sudo apt upgrade -y
```
# 5. Backend
```bash
cd Backend
sudo apt install python3
pip install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
# 8. Frontend
```bash
cd ..
cd Frontend
npm install
npm start
```
