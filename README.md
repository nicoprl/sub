# sub

Python CLI for downloading english subtitles from [http://api.thesubdb.com](http://api.thesubdb.com)

## Prerequisites

Python 3.x

## Installing

`mkdir sub`  
`cd sub`  
`wget https://raw.githubusercontent.com/nicoprl/sub/master/sub`  
Add the `sub` directory to your PATH

## Usage

- open shell in video directory  
- `sub` : download sub for every video file in current folder  
- `sub -f` [movie_file_name]: download sub for movie_file_name only

## Exemple

`$ sub mindhunter.s01e09.720p.webrip.x264-strife\[ettv\].mkv`  
=> file "mindhunter.s01e09.720p.webrip.x264-strife[ettv].srt" is created in current dir

