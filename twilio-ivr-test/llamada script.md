curl.exe -X POST https://api.twilio.com/2010-04-01/Accounts/AC550a225a0713a71e793daf3d00e99f94/Calls.json ^
  --data-urlencode "Url=http://demo.twilio.com/docs/voice.xml" ^
  --data-urlencode "To=+573152045660" ^
  --data-urlencode "From=+12059007980" ^
  -u "AC550a225a0713a71e793daf3d00e99f94:d59144f8fe49d8a0d432366bcbecae53"