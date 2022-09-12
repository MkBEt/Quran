# Amharic Quran API 

Simplified Perfect Complete Amharic Quran JSON REST API.

## Quran JSON Directory Structure

```sh
.
├── title.json          // AL-Quran Title JSON
├── amh                 // Complete Surah JSON Directory
|   └── <number_of:1-114>.json
└── amh/pages           // Complete Pages JSON Directory
    └── <number_of:1-604>.json
```

## Use Of API / Service

### Base GET endpoint

```
https://cdn.jsdelivr.net/gh/MkBEt/quran/api
```

Get Quran Title:

> Get all the details about quran title<br>
```sh
 https://cdn.jsdelivr.net/gh/MkBEt/quran/api/amh/title.json
```

Get Surah:

> Get the chapter 1:<br>
```sh
https://cdn.jsdelivr.net/gh/MkBEt/quran/api/amh/surah/1.json
```

Get Pages:

> Get Page Number 1:<br>
```sh
https://cdn.jsdelivr.net/gh/MkBEt/quran/api/amh/pages/1.json
```
