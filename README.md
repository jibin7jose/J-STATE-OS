# J-STATE-OS


>>jstate checkout main
>> jstate set env dev
>> 
>> jstate branch prod
>> jstate checkout prod
>> jstate set env prod
>> 
>> jstate diff main prod
>> 
✔ switched to main
✔ OK
✔ branch created: prod
✔ switched to prod
✔ OK
{
  "requestId": 1769015474173,
  "from": "main",
  "to": "prod",
  "diff": {
    "added": {},
    "removed": {},
    "changed": {
      "env": {
        "from": "dev",
        "to": "prod"
      }
    }
  }
}



jstate explain diff main prod
>> 
{
  requestId: 1769017617376,
  explanation: [ 'Key "version" was added with value "2"' ]
}

