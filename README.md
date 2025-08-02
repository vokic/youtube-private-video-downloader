🎬 YT Downloader - Simple Restricted YouTube Video Downloader

📦 HOW TO USE:

1. 🧁 **GET YOUR COOKIES.TXT FILE**
   - Install the **"Get cookies.txt LOCALLY"** Chrome extension:
     https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
   - Go to the **YouTube video page** in Chrome.
   - Click the extension icon and choose **"Export All Cookies"**.
   - Save the file as `cookies.txt` on your computer.

2. 🔗 **COPY THE YOUTUBE VIDEO LINK**
   - Use only the base part of the URL (remove everything after `&` if present).
   - Example: `https://www.youtube.com/watch?v=kakAp39b-Xx`

3. 📥 **DOWNLOAD THE VIDEO**
   - Download the app here  https://raw.githubusercontent.com/vokic/youtube-private-video-downloader/main/yt_private_downloader_gui.exe
   - Open `yt_private_downloader_gui.exe`.
   - Paste the YouTube URL.
   - Browse and select your `cookies.txt` file.
   - Click **Download**.
   - The video will be downloaded to the same folder where this app is located.

⚙️ **USES (already included):**
- yt-dlp (Python-based downloader)
- ffmpeg (used to combine video + audio, located in the `bin/` folder)

🗃️ **NOTES:**
- Only one video at a time, supports playlist downloading.
- Do not close the app during the download.

💡 **TIP:**
If nothing downloads, make sure the `cookies.txt` file is correct.
