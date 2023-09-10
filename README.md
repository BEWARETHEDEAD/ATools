# ATools
Tools For TON

cur: v.0.1.1

**Installation**
```shell
pip install git+https://github.com/BEWARETHEDEAD/ATools.git
```


**Navigation**
- [Rest Requests](#rest-requests)

Rest Requests
=============================

```python
import ATools

response = await ATools.Rest.get(url: str, headers: dict, data: dict, json: dict) 
# or
response = await ATools.Rest.post(url: str, headers: dict, data: dict, json: dict)


status_code = response.status
json_answer = response.json
text_answer = response.text


# sending a repeated request by a variable reference

response = await response.update()
```
