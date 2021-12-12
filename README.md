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
python -m venv venv              #for first time only
source venv/bin/activate
```
  if windows:
  ```
   python -m venv venv
   venv\Scripts\activate
   ```
 
 then:
`FLASK_ENV=development`

for windows:
`set FLASK_ENV=development`

and finally:

`flask run`

To use it without ngrok and on LAN:
1. Open your 5000 port in firewall.
2. use command: `flask run --host=0.0.0.0`
