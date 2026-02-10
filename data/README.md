# Data

## Game Table

| Variable           | Description                                         |
| ------------------ | --------------------------------------------------- |
| BGGId              | BoardGameGeek game ID                               |
| Name               | Name of the game                                    |
| Description        | Description, stripped of punctuation and lemmatized |
| YearPublished      | First year the game was published                   |
| GameWeight         | Game difficulty/complexity rating                   |
| AvgRating          | Average user rating for the game                    |
| BayesAvgRating     | Bayes weighted average rating                       |
| StdDev             | Standard deviation of Bayes Avg                     |
| MinPlayers         | Minimum number of players                           |
| MaxPlayers         | Maximum number of players                           |
| ComAgeRec          | Community's recommended age minimum                 |
| LanguageEase       | Language requirement complexity                     |
| BestPlayers        | Community-voted best player count                   |
| GoodPlayers        | List of community-voted good player counts          |
| NumOwned           | Number of users who own this game                   |
| NumWant            | Number of users who want this game                  |
| NumWish            | Number of users who wishlisted this game            |
| NumUserRatings     | Number of user ratings                              |
| NumComments        | Number of user comments                             |
| NumAlternates      | Number of alternate versions                        |
| NumExpansions      | Number of expansions                                |
| NumImplementations | Number of implementations                           |
| IsReimplementation | Binary - Is this listing a reimplementation?        |
| Family             | Game family                                         |
| Kickstarted        | Binary - Was this game funded via Kickstarter?      |
| Rank:boardgame    | Overall board game rank                             |
| Cat                | Categorical variable for game type                  |
| PrimaryTheme       | Most relevant theme assigned to the game            |
| PrimaryMechanic    | Most relevant mechanic assigned to the game         |

### Mechanics Table

| Variable          | Description                            |
| ----------------- | -------------------------------------- |
| BGGId             | BoardGameGeek game ID                  |
| Various Mechanics | Binary flags indicating game mechanics |

### Themes Table

| Variable       | Description                         |
| -------------- | ----------------------------------- |
| BGGId          | BoardGameGeek game ID               |
| Various Themes | Binary flags indicating game themes |


