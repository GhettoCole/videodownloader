# videodownloader
A Simple Script writtten in Python to Download YouTube Videos
These videos can also be downloaded as audio

### Installation
1. Clone the Repo
```Bash
cd videodownloader
# run pipenv shell
pipenv shell
# Then install the dependencies
pipenv install
# To Run the script 
python3 script.py
```

### Usage

You can either run the script directly for interactive mode, or use the command line arguments.

    python script.py
    python script.py -u rfscVS0vtbw -o videos/ -f my_downloaded_video
    python script.py -u rfscVS0vtbw -o audio/ -f my_downloaded_audio --audio-only
    
    -u --url            YouTube URL or YouTube Video ID to download
    -o --output-path    Output Directory Path
    -f --filename       Override the output filename. Does not override file extension
    -a --audio-only     Download Auido Only
    


If you would like to suggest changes feel free to fork this repo and create PR or submit an issue

Feel Free to DM on twitter if you have any questions
[twitter](http://www.twitter.com/muhammad_o7)
Here's the demo on how to use it
[Demo](https://vimeo.com/281200561)
