# Youtube-Audioset-scraper
Searches Youtube for the top videos based on your desired labels. Downloads them as mp3 files and converts to wav files. Cuts the file into 2 second segments then shows spectrogram of each. Combines the files and shows the spectrogram. 
Audio-spectrogram focuses on any random video from youtube based on a search and provides a spectrogram reading.

Audioset scraper focuses on the Google dataset: https://research.google.com/audioset. The file retrieves a random video from the dataset based on the desired label and type (i.e. evaluated music videos).
You can take out the randomness and keep the entire set of ids from the desired dataset and download them in an mp3 or wav format. Both formats are downloaded in the file.


Requires BeautifulSoup and youtube_dl. Does not require a webdriver since we are accessing the js files directly. 
