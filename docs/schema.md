### 1. Kolekcja: `filmy`

| Pole            | Typ    | Opis                                      | Przykład |
| :-------------- | :----- | :---------------------------------------- | :------- |
| `tytul`         | String | Tytuł filmu                               | "Uciekaj!" |
| `data_premiery` | Date   | Data wejścia filmu do kin                 | 2017-02-24 |
| `gatunki`       | Array  | Lista gatunków filmu (może być wiele)     | ["Horror", "Komedia"] |



### 2. Kolekcja: `obsada`

| Pole      | Typ      | Opis                                               | Przykład |
| :-------- | :------- | :------------------------------------------------- | :------- |
| `film_id` | ObjectId | Id filmu z kolekcji `filmy`                       | ObjectId("65f1a2b3c4d5e6f7a8b9c0d1") |
| `rezyser` | String   | Reżyser filmu                                     | "Greta Gerwig" |
| `aktorzy` | Array    | Lista wszystkich aktorów (dowolna liczba)         | ["Margot Robbie", "Ryan Gosling", "America Ferrera"] |


### 3. Kolekcja: `recenzje`

| Pole       | Typ      | Opis                                                     | Przykład |
| :--------- | :------- | :------------------------------------------------------- | :------- |
| `film_id`  | ObjectId | Id filmu z kolekcji `filmy`                              | ObjectId("65f1a2b3c4d5e6f7a8b9c0d1") |
| `widz_id`  | ObjectId | Id widza (unikalny użytkownik systemu)                  | ObjectId("75a2b3c4d5e6f7a8b9c0e2f3") |
| `ocena`    | Number   | Ocena filmu w skali 1–10                                 | 8 |
| `recenzja` | String   | Krótka opinia widza                                      | "Świetna gra aktorska i klimat." |


