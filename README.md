# Simple SMS Blaster
Simple API Request based SMS blaster with the use of CSV

### Setup (Local)
1. clone this repo
2. run `npm install`
3. setup `.env` according to `.env.example`
4. run `npm start`

### POSTMAN upload csv
1. url Local:8080/Upload
2. body > form-data 
3. key:"name" > file > upload csv file
### Sample CSV
```
6512341234,This is a text
6556785678,This is another text
```