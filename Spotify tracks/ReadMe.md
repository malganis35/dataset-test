# Description

### Spotify Dataset

- This month we are analyzing the tracks of Spotify!
- Can we identify what makes a hit track?



# Data Dictionnary

### Structure

#### Primary

- – id (Id of track generated by Spotify)

#### Numerical

- – acousticness (Ranges from 0 to 1)
- – danceability (Ranges from 0 to 1)
- – energy (Ranges from 0 to 1)
- – duration_ms (Integer typically ranging from 200k to 300k)
- – instrumentalness (Ranges from 0 to 1)
- – valence (Ranges from 0 to 1)
- – popularity (Ranges from 0 to 100)
- – tempo (Float typically ranging from 50 to 150)
- – liveness (Ranges from 0 to 1)
- – loudness (Float typically ranging from -60 to 0)
- – speechiness (Ranges from 0 to 1)

#### Dummy

- – mode (0 = Minor, 1 = Major)
- – explicit (0 = No explicit content, 1 = Explicit content)

#### Categorical

- – key (All keys on octave encoded as values ranging from 0 to 11, starting on C as 0, C# as 1 and so on…)
- – timesignature (The predicted timesignature, most typically 4)
- – artists (List of artists mentioned)
- – artists (Ids of mentioned artists)
- – release_date (Date of release mostly in yyyy-mm-dd format, however precision of date may vary)
- – name (Name of the song)
