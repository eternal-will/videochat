# videochat

`create a twilio account`

.env example:
```
TWILIO_ACCOUNT_SID= 
TWILIO_API_KEY_SID= 
TWILIO_API_KEY_SECRET=
```

run:
```
python3 -m venv venv              #for first time only
source venv/bin/activate
```
  if windows:
  ```
   python -m venv venv
   venv\Scripts\activate
   ```

then:
`pip3 install -r requirements.txt`

for windows:
`pip install -r requirements.txt`

and then:
`FLASK_ENV=development`

for windows:
`set FLASK_ENV=development`

and finally:

`flask run`

