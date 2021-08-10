<h1> How it Works </h1>
Nyaa Downloader is a lightweight and user-friendly tool that allows to you to downlod many .torrent (or transfer magnets) at a time. <br>
This tool was made in a way so that the user will almost never be able to make the script crash or run an unhandled exception (WIP).<br><br>
If you want to add a provider like <a href=https://beta.erai-raws.info><b>Erai-Raws</b></a> or <a href=https://subsplease.org><b>SubsPlease</b></a> etc., you'll need to edit the list in the script.
Since they are the only two uploaders that are mainly active and trusted by Nyaa.si, I decided to only put those two. Feel free to add any other uploader you trust.<br><br>

You specify the anime name, the episode where you want to start downloading, and then the last episode. You can also select the quality and download multiple anime at a time.<br><br>
Most importantly, you can choose whether you want to download them as a .torrent or if you only want to open them in your torrent client by using magnet links.

It's really fast, even if the code can probably be improved (be indulgent, I'm still a beginner).<br>
Every downloaded torrent will be stored in a folder (names wil be the anime names) in the same folder as the script under the name `DownloadedTorrents`.
<br><br>
<h1>Requirements (only if you use the Python script)</h1>

With the command `pip install <library>` you'll need to install the following ones :
  
  • NyaaPy<br>
  • win10toast<br>
  • requests<br>
  
You need to be on a Windows 10 machine, of course.
  
To install them in one command, just download the `requirements.txt` and `cd <path>` with the cmd to where the file is located. Then run the following command: `pip install -r requirements.txt` and it should be done!<br><br>
<h1>Important Note for the binary (.exe) from the release</h1>
<a href=https://github.com/jithurjacob/Windows-10-Toast-Notifications>win10toast</a> doesn't work at all with <a href=https://pypi.org/project/auto-py-to-exe/>PyToExe</a> (nor Pyinstaller) so I used another library called `plyer` which allows me to use windows 10 toasts notifications (as a replacement for win10toast).<br><br>
I still prefer using win10toast for the python file because it's still widely used (more than plyer) and I will probably add callback functions with the <a href=https://github.com/vardecab/win10toast-click>win10toast-click</a> in a future release.

  
  <h1> WORK IN PROGRESS </h1>

I will add more features when it will come to my mind. Feel free to contribute to this project by posting your suggestions in the <b>Issue</b> section.
