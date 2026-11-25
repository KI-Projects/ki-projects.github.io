# ki-projects.github.io

<h3>How to work with original photos/video in Hydra</h3>
In order to reference a photo or video of your own in the Hydra web platform, you need to upload it somewhere on the internet and be able to get the exact URL of that file. I have created a GitHub repository for this purpose. Keep in mind GitHub only accepts videos that are less than 25 MB (about 20 seconds long) and they can't be .mov files. Also keep in mind, I did not have the option of making this repository private, so all content you upload is potentially viewable/downloadable by the public. BUT - I highly doubt anyone will stumble across this page in the next couple of weeks and I will delete once our class is finished. :) Here are the steps:<Br><br>
<b>First, convert your video to MP4 (Skip for photos):</b><br>
<ol>
<li>Share your video from your phone to your computer.</li>
<li>Locate your file on your computer and add your name to the filename, keeping the extension unchanged (i.e. IMG_1597-Sara.mp4).</li>
<li>Head over to <a href="https://express.adobe.com/" target="_blank">https://express.adobe.com/</a> and log in using your VCU email credentials.</li>
<li>Type "mp4" into the Search bar and click on "Convert to MP4" in the options that pop up.</li>
<li>Drag and drop your video file into the window.</li>
<li>After the video uploads, you can trim it if you want. (About 20 seconds is the max for keeping the file under 25MB).</li>
<li>Download your video by clicking the download icon to the right of "open in editor". It will now have an .mp4 extension.</li>
</ol>
<b>Now, upload to GitHub:</b><br>
<ol>
<li>Navigate to <a href="https://github.com/KI-Projects/ki-projects.github.io" target="_blank">https://github.com/KI-Projects/ki-projects.github.io</a>.</li>
<li>Click <b>Sign in</b> in the upper right corner and use the credentials from our <a href="https://virginiacommonwealth.instructure.com/courses/139995/assignments/1611421" target="_blank">assignment sheet</a>.</li>
<li>Find the green "code" button and click the button to the left of it. It might look like a + icon or it might be a button that says "Add file." Then select "Upload files".</li>
<li>Drag and drop your photo (.jpg or .gif) or video (.mp4 only) file into the window. Files must be less than 25MB.</li>
<li>Click the green "Commit changes" button at the bottom of the page. Note - if you don't do this your file won't upload!</li>
<li>After your file uploads, it will show up in the repository list.</li>
</ol>
<b>Referencing the file in Hydra: </b><br>
We can tell Hydra the location your file by simply adding the filename to the end of this page's URL, after the slash - <a href="https://ki-projects.github.io">https://ki-projects.github.io/</a>. So, if you uploaded a video with the filename IMG_1597-Sara.mp4, your code will look like this:<br><br>

<i>s0.initVideo("https://ki-projects.github.io/IMG_1597-Sara.mp4")<br>
src(s0).out()</i>
<br><br>
You can then add on functions just like you would with any other source. <a href="https://hydra.ojack.xyz/?code=JTJGJTJGRXhhbXBsZSUyMGZvciUyMGluY2x1ZGluZyUyMG9yaWdpbmFsJTIwdmlkZW8hJTIwJTBBJTJGJTJGU2VlJTIwZnVsbCUyMHVwbG9hZCUyMGluc3RydWN0aW9ucyUyMGF0JTIwaHR0cHMlM0ElMkYlMkZraS1wcm9qZWN0cy5naXRodWIuaW8lMEElMEFzMC5pbml0VmlkZW8oJTIyaHR0cHMlM0ElMkYlMkZraS1wcm9qZWN0cy5naXRodWIuaW8lMkZJTUdfMTU5Ny1TYXJhLm1wNCUyMiklMEFzcmMoczApJTBBLm1vZHVsYXRlKCUwQSUwOXNoYXBlKDQlMkMwLjgpJTBBKSUwQS5tb2R1bGF0ZSglMEElMDlzaGFwZSg0KSUwQSklMEEub3V0KG8wKSUwQSUwQSUwQQ%3D%3D" target="_blank">See this Hydra example.</a>

