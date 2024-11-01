## Jnx LLM For Thai
### How to use

Key code : "Authorization": "Bearer Jnx03Authen-21sadfsdl;joi23oinoisjeoi2joijLKsnb3ilBDJVNl3isl2",  (limit 100 global message/s)


- python
```python
import requests

url = 'https://chat.jnx03.xyz/api'

headers = {
    "Authorization": "Bearer Jnx03Authen-21sadfsdl;joi23oinoisjeoi2joijLKsnb3ilBDJVNl3isl2", 
    "Content-Type": "application/json"
}

payload = {
    "model": "Jxxn03z-V1-70B",
    "max_tokens": 512,
    "messages": [
        {"role": "user", "content": "Hello, how are you?"}
    ],
    "temperature": 0.4,
    "top_p": 0.9,
    "top_k": 0,
    "repetition_penalty": 1.05,
    "min_p": 0.05
}

response = requests.post(url, json=payload, headers=headers)

if response.status_code == 200:
    print("Response:", response.json())
else:
    print("Error:", response.status_code, response.text)
```
- javascript

```javascript
const url = 'https://chat.jnx03.xyz/api';

const headers = {
    "Authorization": "Bearer Jnx03Authen-21sadfsdl;joi23oinoisjeoi2joijLKsnb3ilBDJVNl3isl2",
    "Content-Type": "application/json"
};

const payload = {
    "model": "Jxxn03z-V1-70B",
    "max_tokens": 512,
    "messages": [
        {"role": "user", "content": "Hello, how are you?"}
    ],
    "temperature": 0.4,
    "top_p": 0.9,
    "top_k": 0,
    "repetition_penalty": 1.05,
    "min_p": 0.05
};

fetch(url, {
    method: 'POST',
    headers: headers,
    body: JSON.stringify(payload)
})
.then(response => response.json())
.then(data => console.log("Response:", data))
.catch(error => console.error("Error:", error));```
