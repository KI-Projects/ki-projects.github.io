# ki-projects.github.io

<h3>How to work with original photos/video in Hydra</h3>
In order to reference a photo or video of your own in the Hydra web platform, you need to upload it somewhere on the internet and be able to get the exact URL of that file. I have created a GitHub repository for this purpose. Keep in mind GitHub only accepts videos that are less than 25 MB (about 20 seconds long) and they can't be .mov files. Also keep in mind, I did not have the option of making this repository private so all content you upload is potentially downloadable by the public. However, I highly doubt anyone will stumble across this page in the next couple of weeks and I will delete once our class is finished. Here are the steps:<Br><br>
<b>First, convert your video to MP4 (Skip for photos):</b><br>
<ol>
<li>Share your video from your phone to your computer.</li>
<li>Locate your file on your computer and add your name to the filename, keeping the extension unchanged (i.e. IMG_1597-Sara.mp4).</li>
<li>Head over to https://express.adobe.com/ and log in using your VCU email credentials.</li>
<li>Type "mp4" into the Search bar and click on "Convert to MP4" in the options that pop up.</li>
<li>Drag and drop your video file into the window.</li>
<li>After the video uploads, you can trim it if you want. (About 20 seconds is the max for keeping the file under 25MB).</li>
<li>Download your video by clicking the download icon to the right of "open in editor". It will now have an .mp4 extension.</li>
</ol>
<b>Now, upload to GitHub:</b><br><br>
<ol>
<li>Navigate to https://github.com/KI-Projects/ki-projects.github.io and sign in with the credentials I posted in our assignment sheet.</li>
<li>Click the + icon to the left of the green "code" button and select "Upload files".</li>
<li>Drag and drop your photo (.jpg or .gif) or video (.mp4 only) file into the window. Files must be less than 25MB.</li>
<li>Click the green "Commit changes" button at the bottom of the page. Note - if you don't do this your file won't upload!</li>
<li>After your file uploads, it will show up in the repository list.</li>
</ol>
<b>Referencing the file in Hydra: </b>
<br><br>
Now we can tell Hydra where to look for your file by simply adding the filename to the end of this page's URL: https://ki-projects.github.io/filename.mp4 or https://ki-projects.github.io/filename.jpg. So, if your filename is IMG_1597-Sara.mp4, your code will look like this:<br><br>

s0.initVideo("https://ki-projects.github.io/IMG_1597-Sara.mp4")
src(s0).out()
