[![PyPI version](https://badge.fury.io/py/song.svg)](https://badge.fury.io/py/song)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/ankitmathur3193/song-cli/blob/master/LICENSE)
# SONG DOWNLOADER #
A **command line** interface for **downloading Bollywood and Punjabi Songs** from Internet
## For Installing ##
```
pip install song
```
## For Upgrading ##
```
pip install --upgrade song
```
## For Uninstalling ##
```
pip uninstall song
```
## Usage: ##
```
song -d [ song_name | artist_name | movie_name ]
```
## Example: ##
* ### For Downloading Song (It will download the file in current working directory) ###
    ```
    song -d tum hi ho
    ```
    
    ![song-cli example](https://cloud.githubusercontent.com/assets/15183662/26523026/cdc7d2e6-432a-11e7-941b-76fa9c465093.png)


* ### For Listing songs of a Movie 
  ```
     song -d dangal
  ```
  
    ![after movie name](https://cloud.githubusercontent.com/assets/15183662/26523019/b009e7b2-432a-11e7-8241-919f95c993bf.png)
  
 
 * ### For Listing Top songs of a Artist ###
    ```
    song -d sunidhi chauhan     
    ```
 
    ![artist_top_songs](https://cloud.githubusercontent.com/assets/15183662/26523023/c1a272dc-432a-11e7-85e7-1757a40da341.png)
 
## TODO ##

- [ ] Implement Unit Testing
- [ ] Add support for Hollywood/English Songs
- [ ] Option for downloading all songs of a movie
- [ ] Option for downloading all top songs of a artist

## Want to Contribute ##
- Clone the repository

```
$ git clone https://github.com/ankitmathur3193/song-cli.git
```
  
 - Install dependencies
 
```
$ pip install -r requirements.txt
``` 

 
 



----------------------------------------------------


