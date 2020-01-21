# Just Chat

Just chat is a real-time chat application build with react.js and Django

## Installation

The application consists of two parts:
1. Backend
2. Frontend

steps to make backend up and running
```bash
python3 -m venv <env name>
```
```bash
source <env name>/bin/activate>
```
```bash
pip3 install -r requirements.txt
```
```bash
python manage.py runserver
```

steps to make frontend up and running

```json
npm i
npm start
```
## Usage

```
1. Create two users (easiest way might be to run `python manage.py createsuperuser` twice)
2. Using django admin, create a `Contact` object for each user.
3. Make sure you have an instance of redis running. 
```