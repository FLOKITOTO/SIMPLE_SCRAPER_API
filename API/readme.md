The project is realized in python with flask and a MongoDB database

[MongoDB_API]

- read
- write
- update
- delete


REQUETTES 

- GET 
- POST
- PUT
- DELETE


SYNTAX

[GET]

```json
{
    "database": "local",
    "collection": "mozilla",
    "Document": {}
}
```

[POST]

```json
{
    "database": "local",
    "collection": "mozilla",
    "Document": {
        "Program Name": {
            "0": "Python",
            "1": "Pascal",
            "2": "Lisp",
            "3": "D#",
            "4": "Cobol",
            "5": "Fortran",
            "6": "Haskell"
        },
        "Internet Points": {
            "0": 932914021,
            "1": 532,
            "2": 1522,
            "3": 12,
            "4": 3,
            "5": 52124,
            "6": 24
        },
        "Kittens?": {
            "0": "Definitely",
            "1": "Unlikely",
            "2": "Uncertain",
            "3": "Possibly",
            "4": "No.",
            "5": "Yes.",
            "6": "lol."
        }
    }
}
```

[PUT]

```json
{
    "database": "local",
    "collection": "mozilla",
    "Filter": {
        "Program Name": {
                "0": "Python",
                "1": "Pascal",
                "2": "Lisp",
                "3": "D#",
                "4": "Cobol",
                "5": "Fortran",
                "6": "Haskell"
            }
    },
    "DataToBeUpdated": {
            "Internet Points": {
                "PPIERRRE": 6666666,
                "1": 532,
                "2": 1522,
                "3": 12,
                "4": 3,
                "5": 52124,
                "6": 24
            }
    }
}
```

[DELETE]

```json
{
    "database": "local",
    "collection": "mozilla",
    "Filter": {
     "Program Name": {
        "0": "Python",
        "1": "Pascal",
        "2": "Lisp",
        "3": "D#",
        "4": "Cobol",
        "5": "Fortran",
        "6": "Haskell"
        }
    }
}
```

[TAG]

MongoDB
Flask
Python
CRUD

Put data to DATABASE WITH API
API 
INSERT DATA WITH API TO database
Insert data with api to database MongoDB
Simple scraper API 
scraper API to MongoDB
MongoDB