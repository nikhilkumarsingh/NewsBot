# MyBot

## Steps to run above code

### 1. Create and activate virtual environment

- Install **virtualenv**
    ```
    pip install virtualenv
    ```
    
- Create virtual environment in project directory
    ```
    virtualenv venv
    ```
    
- Activate virtual environment
    ```
    source venv/bin/activate
    ```
    For windows:
    ```
    venv\Scripts\activate
    ```
    
### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run flask app

```
python app.py
```

### 4. Setup ngrok

Download from here: https://ngrok.com/

Open terminal in the folder where ngrok has been installed and run:

```
ngrok http 8000
```

### 5. Setup webhook

Edit/setup the webhook for your facebook app.


Test the bot! :)
