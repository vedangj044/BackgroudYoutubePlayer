# BackgroudYoutubePlayer

A python program to play youtube videos in the backgroud. With bandwith limitation, videos play at the 144p thus consuming the least amount of data possible. Also a bat file enables us to run this program from the run window itself. 

To use :- 
1. Edit the 'path' environment variable, adding a path to the folder you keep these files in.
2. Open run window and type in 'w' + the name of the song or video (keep this such that the first result is the video you want to play).
    use double quotes to pass arguments of multile words.

<strong>What did i do ?</strong></br>
It is quite easy, most of you might have guessed it. I used Selenium python library to open a browser window, made it invisible by </br>`chrome_options.add_argument("--headless")`
 </br>`browser = webdriver.Chrome(options=chrome_options)`
 </br>The Programs an argument, which search for that query on youtube, fetches result, the script after which clicks on the first video link and the video starts playing.

<strong>Why it is better than Pafy?</strong>
 </br>I know it would be a lot easier to download the particular video and convert it to mp3, but thus it supports privacy. Here as we are not extracting music out of it, It seems to be a more honest option. Also, the youtube autoplay option adds to the great expreince.
