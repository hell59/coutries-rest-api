# 🌎 Countries REST API

A Simple countries REST API, build for learning purposes

## Getting countries:

```
GET https://tads-countries-api.herokuapp.com/countries/
```

## Getting a single country:

```
GET https://tads-countries-api.herokuapp.com/countries/607ba400ad235865fe8130dd
```

## Creating countries:


```
POST https://tads-countries-api.herokuapp.com/countries/
```


```json
{
  "name": "Brasil",
  "capital": "Brasilia",
  "currency": "Real",
  "language": "Portugues",
  "population": 210000000,
  "area": 8000000
}
```

## Updating countries:

```
PUT https://tads-countries-api.herokuapp.com/countries/607ba400ad235865fe8130dd
```


```json
{
  "name": "Republica Federativa do Brasil",
  "capital": "Brasilia",
  "currency": "Real",
  "language": "Portugues do Brasil",
  "population": 210000000,
  "area": 8000000
}
```
## Deleting countries:

```
DELETE https://tads-countries-api.herokuapp.com/countries/607ba400ad235865fe8130dd
```
