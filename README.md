# songsAsAClass
A small project to test and manipulate
The first step is to define a class Song, which holds the following information about songs: typeList, name, and time.
The input is an array.
The first element n must be the number of songs. Next n elements must be the songs data in the following format:
"{typeList}_{name}_{time}", and the last element must be typeList / "all".

We print only the names of the songs, which have the same typeList (obtained as the last parameter). If the value of the
last element is "all", print the names of all the songs.

For example: an input could be:
[3,
'favourite_DownTown_3:14',
'favourite_Kiss_4:16',
'favourite_Smooth Criminal_4:01',
'favourite']

With an intended output of: 
DownTown
Kiss
Smooth Criminal

Another example:
[4,
'favourite_DownTown_3:14',
'listenLater_Andalouse_3:24',
'favourite_In To The Night_3:58',
'favourite_Live It Up_3:48',
'listenLater']
With Output: 
Andalouse

