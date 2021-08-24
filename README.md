<h1>❓ How it Works </h1>
NyaaDownloader is a lightweight and user-friendly tool that allows to you to downlod many .torrent (or transfer magnets) at a time. <br><br>
This tool was made in a way so that the user will almost never be able to make the script crash or run an unhandled exception.<br><br>
The search engine is based on Nyaa.si one and the way the script look for episode is constantly improved to avoid errors and differenciate the way uploaders name their torrents.<br><br>
If you want to add or remove a provider (uploader) like <a href=https://beta.erai-raws.info><b>Erai-Raws</b></a> or <a href=https://subsplease.org><b>SubsPlease</b></a> etc., well... you can, directly in the console!<br>
Since they are the only two uploaders that are mainly active and trusted by Nyaa.si, I decided to only put those two. Feel free to add any other uploader you trust (and remove the ones that you're not interested in).<br><br>

You specify the anime name, the episode where you want to start downloading, and then the last episode. You can also select the quality and download multiple anime at a time.<br><br>
Most importantly, you can choose whether you want to download them as a .torrent or if you only want to open them in your torrent client by using magnet links.

At the end of the execution, if the checking wasn't 100% successful, you'll get a .txt file which contains every single episode that couldn't be downloaded.
Downloaded .torrent files will be sorted into their respective folders.

It's really fast, even if the code can probably be improved (be indulgent, I'm still a beginner).<br>
Every downloaded torrent will be stored in a folder (names wil be the anime names) in the same folder as the script under the name `DownloadedTorrents`.
<br>

You need to be on a Windows 10 machine, of course.<br>
You'll also need a BitTorrent client to open .torrent files and magnet links.<br><br>

<h1>📌 Requirements (only if you use the Python script)</h1>

With the command `pip install <library>` you'll need to install the following ones :
  
  • NyaaPy<br>
  • winotify<br>
  • requests<br>
  
To install them in one command, just download the `requirements.txt` and `cd <path>` with the cmd to where the file is located. Then run the following command: `pip install -r requirements.txt` and it should be done! Python version: `3.9.1` but should works with any `3.0+` version.<br>
  
<h1>⚙️ Work in progress</h1>

I will add more features when it will come to my mind.<br>
Feel free to contribute to this project by posting your suggestions in the <b>Issue</b> section.<br><br>


<h1>🐍 The script in action</h1>

This quick video shows you how the script works (without trying to make it crash (of course, you won't succeed in making it crash 👀))<br><br>
<b>Fun fact:</b>
<br>As you might have seen, in the video, the first episode of <i>Boku no Hero Academia 5th Season</i> wasn't the good one.<br>The script took the most recent one which happened to have a title similar to a batch release.<br>I found a way to fix that and it now works. I won't make the video again since it takes a lot of time (lol)

https://user-images.githubusercontent.com/52708150/130366440-2635b482-07bc-4df4-8b5e-b64fd2f0dd9c.mp4

