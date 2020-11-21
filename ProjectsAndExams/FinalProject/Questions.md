# CPSC 392 Final Project (Part 2)

### Dan Haub, Keivan Golchini, Trevor Skyes

## Data Set:

-   Spotify Dataset 1921-2020, 160k+ Tracks ([Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks))

## Variables:

(Descriptions taken directly from the [Kaggle dataset](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks) and the [Spotify Developer API Documentation](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-analysis/))

-   acousticness
    -   A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
-   artists
    -   A list of artists credited for the track.
-   danceability
    -   Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.
-   duration_ms
    -   The duration of the track in milliseconds.
-   energy
    -   Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.
-   explicit
    -   Whether or not the track contains explicit content.
    -   0: no explicit content.
    -   1: some explicit content.
-   id
    -   The Spotify ID for the track.
-   instrumentalness
    -   Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
-   key
    -   The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation . E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
-   liveness
    -   Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
-   loudness
    -   The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db.
-   mode
    -   Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
-   name
    -   The title of the track
-   popularity
    -   The current (at the time of data set creation) popularity of the track. This is measured on a scale from 0-100
-   release_date
    -   The release date of the track
-   speechiness
    -   Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
-   tempo
    -   The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
-   valence
    -   A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
-   year
    -   The year of release for the track

## Questions

1.  Can we predict the release year of a track given the other variables?

1.  Can we classify the genre/style of a track given its characteristics?

1.  Can we classify the mood/tone of the track given its characteristics?

1.  Can we predict if someone would like a track given thier music tastes?

1.  Can we predict if a track is major or minor given it's other characteristics?

1.  Can we predict how popular a track is currently?

1.  Can we determine if a song is "club worthy" or not?
