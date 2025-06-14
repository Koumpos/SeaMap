# SeaMap
## Οδηγίες για την εκτέλεση της εφαρμογής 

### Λήψη του κώδικα
```shell
git clone https://github.com/Koumpos/SeaMap.git
```

### Προετοιμασία περιβάλλοντος εκτέλεσης

```shell
pip install virtualenv
virtualenv .venv
./.venv/Scripts/activate
python -m pip install -r requirements.txt
```

### Εκτέλεση
Σε χωριστά τερματικά εκτελέστε τα παρακάτω

#### 1. Prediction API:
```shell
./.venv/Scripts/activate
cd prediction
python predict_api.py
```

#### 2. Chatbot:
```shell
./.venv/Scripts/activate
cd chatbot
python Chatbot.py
```


#### 3. Ιστοσελίδα με χάρτη:
```shell
./.venv/Scripts/activate
cd web-client
python -m http.server
```
Επισκεφθείτε το http://localhost:8000

