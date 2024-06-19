
# Whatsapp Python

It is project for create with python a bot for whatsapp

## Clone repo

```bash
git clone https://github.com/andrescuello7/bot_whatsapp
```

## Development

```bash
  cd /bot_whatsapp

  virtualenv -p 3.10.11 .venv
  source .venv/bin/activate

  pip install -r requirements.txt
  
  python app.py

  # for running server for tunel in https for default with serveo
  # This project not run in http for Meta Developers API
  ssh -R 80:localhost:8000 serveo.net
```
