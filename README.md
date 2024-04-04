# API Tools Express

Fire equipment server uses Express JS

## Installation
```sh
https://github.com/fitri-hy/api-tools-express.git
npm install
```

## Create & Setup (.env)
```
# port
PORT='5000'

# rate 15 minute
LIMIT_RATE='15 * 60 * 1000'

# limit request
LIMIT_MAX='100'

# message over limit
LIMIT_MESSAGE='Too many requests from this IP, please try again later.'
```

## Create & Setup (index.js)
```
require('api-tools-express');
```

## Run Project
```
node index.js
```

## Api Endpoint
```
http://localhost:5000/translate?text=<QUERY>&from=<FROMLANG>&to=<TOLANG>
http://localhost:5000/wiki/<QUERY>/<LANG>
http://localhost:5000/ip
http://localhost:5000/search?keyword=<QUERY>
```

## Usage Example
```
http://localhost:5000/translate?text=cat&from=en&to=id
http://localhost:5000/wiki/jakarta/id
http://localhost:5000/ip
http://localhost:5000/search?keyword=cat
```

## Support Language
Go to <a href="https://www.ibm.com/docs/en/cognos-controller/10.4.2?topic=codes-language">Language Code</a>

Official Site: <a href="https://hy-tech.my.id/">VISIT</a>

