# Notes-App-Back-End

RESTful API For Notes Deployed On GCP - Cloud Computing Bangkit 2022.

## Routing

| Method | Path | Response Code | Body | Description |
|---|---|---|---|---|
| POST | /notes | 201 | JSON | Create new notes |
| GET | /notes | 200 | JSON | Get a list of notes |
| GET | /notes/:id | 200 | JSON | Get note details |
| PUT | /notes/:id | 200 | JSON | Update notes |
| DELETE | /notes/:id | 200 | JSON | Delete notes |

## Data structure

```JSON
{
    "id": "notes-V1StGXR8_Z5jdHi6B-myT",
    "title": "Sejarah JavaScript",
    "createdAt": "2020-12-23T23:00:09.686Z",
    "updatedAt": "2020-12-23T23:00:09.686Z",
    "tags": ["NodeJS", "JavaScript"],
    "body": "JavaScript pertama kali dikembangkan oleh Brendan Eich dari Netscape di bawah nama Mocha, yang nantinya namanya diganti menjadi LiveScript, dan akhirnya menjadi JavaScript. Navigator sebelumnya telah mendukung Java untuk lebih bisa dimanfaatkan para pemrogram yang non-Java."
}
```

## Server options

- `port` 5000
- `host` localhost


## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Mochammad Arya Salsabila - Aryasalsabila789@gmail.com
