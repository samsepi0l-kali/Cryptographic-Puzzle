# Puzzle
Solve this Cryptographic Puzzle.

Puzzle Instructions:

1. *Download and Extract the Key Image*:
   - Download the key image file from the server. This file is compressed using a tool like 7-zip. 
   - Use 7-zip to extract the contents of this file. Inside, you'll find a .wav audio file.

2. *Analyze the Audio File*:
   - Open the .wav file in Audacity or a similar audio analysis tool.
   - Plot the spectrogram of the audio. (In Audacity: Click "Analyze" -> "Plot Spectrum" -> "Spectrogram")
   - Look for symbols or patterns in the spectrogram.

3. *Identify Moon Type Symbols*:
   - The symbols you see in the spectrogram are in Moon Type, a writing system for the blind.
   - Use a Moon Type reference guide to decode the symbols. (You can find Moon Type references online or use the attached guide).

4. *Decode the Moon Type Cipher*:
   - Decipher the Moon Type symbols to reveal a phrase. It should be something like "The Fragment is Lost in the Stars".

5. *Modify the URL*:
   - The phrase points to another image on the server.
   - Modify the URL you used to download the initial key image by replacing the key in the URL with "thestars.png" to access the next image. For example, if the original URL was http://example.com/keyimage.png, change it to http://example.com/thestars.png.

6. *Examine the Image Metadata*:
   - Download the new image and examine its metadata. You can use tools like ExifTool or an online metadata viewer.
   - In the metadata, you will find a set of numbers.

7. *Identify DTMF Frequencies*:
   - Perform a web search for the numbers found in the metadata. You'll discover they correspond to DTMF (Dual-Tone Multi-Frequency) frequencies, which are the sounds you hear when pressing a phone key.
   - Use a DTMF reference chart to decode the sets of frequencies into their corresponding key presses.

8. *Decode the Number Sequence*:
   - The key presses will result in a number sequence. Convert this number sequence into letters using a simple text cipher where A=1, B=2, C=3, and so on.
   - Example: If your sequence is 20-8-5-19-20-1-18-19, it decodes to "THESTARS".

9. *Find the Final Flag*:
   - With the decoded sequence, perform any final brainstorming or trial and error to determine the final flag.
   - The flag is the ultimate solution to this puzzle.

---

### Additional Hints and Resources:

1. *7-zip Extraction*:
   - Download 7-zip from [7-zip.org](https://www.7-zip.org/) if you don't have it installed.
   - Use the right-click context menu to extract the contents of the compressed file.

2. *Using Audacity for Spectrograms*:
   - Download Audacity from [audacityteam.org](https://www.audacityteam.org/) if needed.
   - Load the .wav file into Audacity, select the audio track, and use the spectrogram view to analyze the sound.

3. *Moon Type Reference*:
   - Use an online Moon Type reference or the attached guide to translate the symbols.

4. *DTMF Frequencies*:
   - A DTMF reference chart is essential for decoding the frequencies. Here's a basic one:
     ```
     1: 697Hz + 1209Hz
     2: 697Hz + 1336Hz
     3: 697Hz + 1477Hz
     4: 770Hz + 1209Hz
     5: 770Hz + 1336Hz
     6: 770Hz + 1477Hz
     7: 852Hz + 1209Hz
     8: 852Hz + 1336Hz
     9: 852Hz + 1477Hz
     0: 941Hz + 1336Hz
