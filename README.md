# django-react-jwt-authentication

## setup

```
git clone https://github.com/ytanaka44/django-react-jwt-authentication.git
cd django-react-jwt-authentication
```

### python setup

```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### install react packages

```
cd frontend
npm install
```

## 起動方法

### backend

```
cd backend
python manage.py migrate
python manage.py runserver
```

### frontend

```
cd frontend
npm start
```
