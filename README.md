## Rename-key-city-to-location-in-the-following-dictionary
## Sample code to check the location
```sh
sampleDict = {
  "name": "Kelly",
  "age":25,
  "salary": 8000,
  "city": "New york"
}

sampleDict['location'] = sampleDict.pop('city')
print(sampleDict)
```
## Expected output
{
  "name": "Kelly",
  "age":25,
  "salary": 8000,
  "location": "New york"
}
