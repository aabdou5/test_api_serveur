# test_api_serveur
test


### Parser un JSON :
```javascript
//JSON
const data = {
  message: 'Hello world',
}

//JSON stringifié
const string = "{\"message\":\"Hello world\"}"

// JSON complexe exemple
const complexJson = {
  id : 1,
  object : data,
  string : JSON.parse(string)
}

// afficher le JSON sur le client avec JSON.stringify()
$('#msg').html(JSON.stringify(complexJson))

// on peut log le JSON brut dans la console
console.log(complexJson)
```
