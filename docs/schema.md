### 1. Kolekcja: `movies`
| Pole          | Typ Danych  | Opis                  | Przykład                                                                       |
|:--------------|:------------|:----------------------|:-------------------------------------------------------------------------------|
| `_id`         | **Int**     | Id filmu.             | `1`                                                                            |
| `movieTitle`  | **String**  | Nazwa filmu.          | `"Fortnite Movie"`                                                             |
| `dateRelease` | **Number**  | Data wydania filmu.   | `27.05.2031`                                                                   |
| `genres`      | **String**  | Gatunek filmu.        | `Akcja, Komedia`                                                               |
| `actors`      | **String**  | Aktorzy.              | `LeBron James, Jim Carrey, `<br/>` Ryan Gosling, Megan Fox` <br/> `(And More)` |
| `director`    | **String**  | Reżyser.              | `Sean Combs`                                                                   |
| `premium`     | **boolean** | Czy film jest płatny. | `true`                                                                         |

### 2. Kolekcja: `rating`

| Pole         | Typ Danych | Opis                              | Przykład           |
|:-------------|:-----------|:----------------------------------|:-------------------|
| `_id`        | **Int**    | Id recenzji.                      | `1`                |
| `movieTitle` | **String** | Nazwa recenzowanego filmu.        | `"Fortnite Movie"` |
| `comment`    | **String** | Kometntarz do filmu.              | `Wspaniały film`   |
| `rating`     | **Int**    | Ocena recenzowanego filmu (1/10). | `9`                |   