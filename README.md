# Mashup-Song-Recommender
# Checking The Compatibility of Songs from 1924 to 2010 for the production of a Mashup with the Song Input


## Input 

The file songs.csv contains many rows with information about songs from the year 1924 to 2010
. Each row contains the following:
- Title 
- Artist 
- Year
- Popularity
- Duration (in seconds)
- Tempo (in beats per minute(bpm))

My program would be reading only the 'Title' , 'Year' and 'Tempo' for every song in the songs.csv file.

## Output

I would be representing the data of the mashup compatible songs in the form of a line graph which shows the number of songs in each year that can be used to produce a mashup with the song that is input.

Graph/Chart :  Type: Line Graph
 
This would help me in comparing the songs in different tempo ranges and representing the number of songs from every year which have a tempo in the range [BPM - 25, BPM + 25], where BPM is the tempo of the song that has been input.

- The X Axis of the Line Chart would have the years from 1924 to 2010
- The Y Axis of the Line Chart would have the number of Compatible Songs which have their Tempo in the range     mentioned above.
- The Title of the Line Chart is "Total Number of Songs Compatible with " + song_title + " Per Year"

## What problem am I solving?

I want to make a mashup of 2 songs. For this, I would require 2 songs that are actually compatible with each other for the production of a mashup i.e both songs have similar tempos( in the range [bpm - 25, bpm + 25]).

The csv file gives me all the songs from 1924 to 2010. Using my code would give me an overview of the variation in the compatibility of songs from 1924 to 2010 with the song that I'm interested in. This way it'll get easier for me to look for a compatible song.

## Where is the information from?

The songs.csv is sourced from http://millionsongdataset.com

The Million Song Dataset is a freely-available collection of audio features and metadata for a million contemporary popular music tracks.

The core of the dataset is the feature analysis and metadata for one million songs, provided by The Echo Nest. 

## Why is it interesting to me?




The information I chose to represent from SongData are the Song Title, Year, and the tempo. Firstly there would be formation of a filtered list of songs that contains all the SongDatas that are compatible with the SongData that has the same title as the song_title input. Then, there would be a comparision of the tempo of the SongData input with each SongData in the filtered list. The result would be a line chart with the number of compatible songs (Y axis value) and the years (X axis). This would show the variation in the number of songs from 1924 to 2010 compatible to produce a mashup with the song input.

In the past I have worked with different music production softwares and it is always difficult to find songs to make mashups with. This code would definitely help solve that problem by making it easier to find compatible songs.
