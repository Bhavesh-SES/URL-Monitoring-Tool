# URL Playback Monitoring Tool

🧰 ✅ How to Use the Web-Based URL Monitoring Tool
Link: https://bhavesh-ses.github.io/url_player/
 
This tool is designed to help you monitor multiple live video URLs (HLS/DASH) in seconds — with error alerts, automatic refresh, mute toggles, and a downloadable summary log of any playback issues.

🔧 1. Prepare Your URL List in Under 10 Seconds Using Google Sheet
We are using a Google Sheet called URL_Creator which automatically formats the URLs and CSV-ready lines: https://docs.google.com/spreadsheets/d/1O2lwykm8TecUezifPAs8yF3wHrBDSaDyNbMp7qaC__Y/edit?gid=749506384#gid=749506384

📝 Example Output From Sheet:  URL_Player.csv
CH01_HLS,https://live-live-dazn-az-dcg-prda.uksouth-3.streaming.mediakind.com/cmaf/<OAID>/index.m3u8CH01_DASH,https://live-live-dazn-az-dcg-prda.uksouth-3.streaming.mediakind.com/cmaf/<OAID>/manifest.mpd

🚀 Steps to Generate CSV-Ready URLs: 
Step	Action
1️⃣	Open your URL_Creator Google Sheet for MK URL's
2️⃣	Paste OAID list into Column B (for HLS) and/or Column G (for DASH)
3️⃣	Get auto-generated URLs in Column C (HLS) and Column H (DASH)
4️⃣	Copy the final concatenated CSV rows from Column D (for HLS) &Column I (for DASH)
5️⃣	Paste into a .csv file (e.g., streams.csv) and save
 
⏱️ This reduces 30+ minutes of manual work into under 10 seconds!

🌐 2. Open the Web Tool in Browser
Open  https://bhavesh-ses.github.io/url_player/  in your browser

🧮 3. Choose Layout & Load Players
At the top:
Set Rows (e.g. 5)
Set Columns (e.g. 2)
Set Max Players Per Page (optional, e.g. 10)
Set Auto Refresh Interval (e.g. 2 min)
📌 This lets you control how many players to show per page and how often they reload.
Then click "Apply Layout"

📁 4. Upload CSV File
Now: Either drag & drop your .csv file directly into the browser window Or click the file input and choose your file
✅ Once uploaded, video players will appear as per your chosen layout.

🔊 5. Smart Controls Available
Control	Description
🌗 Theme Toggle	Switch between light/dark mode
🔔 Mute Alarm	Disable/Enable alert sound for playback errors
🔇 Mute All URLs	Mute or unmute audio of all videos on screen
⬅ Prev / Next ➡	Navigate between pages of player boxes
📥 Download Summary Log	Exports a .csv of all playback issues (name, URL, timestamp, status)
 
🚨 6. When a URL Fails
If any URL fails:
A red error alert appears below the player
If mute alarm is OFF, alert.mp3 rings, it's added to flag if any URL is not working/loading/Playing
The issue is logged for download (includes time + error type)
✅ 7. Benefits Recap
 
🚀 Time Saved	                                        ⏱ Before	                              ⚡ Now
Manually creating each HLS/DASH URL  	            ~10–15 mins per page	          ⏱ Under 10 seconds via URL_Creator
Copy-pasting into CSV format	                    Manual & error-prone	          🔁 Auto-generated in Column D/I
Monitoring 10+ URLs simultaneously	              Requires multiple tabs	        🖥️ All-in-one dashboard with error logs
Troubleshooting issues	                          Manual screenshots + notes	    📥 One-click log download with full timestamped records

