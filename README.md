# Music Curation Project
## Each Weeks' Tasks
 [Week 1](#week-1-musical-datasets) 
 
 [Week 2](#week-2-using-musescore) 
 
 [Week 3](#week-3-music-xml-files)

 [Week 4](#week-4-jsymbolic-and-music21)

 [Week 5](#week-5-editing-mei-code)

 [Week 7](#week-7-mei-copyright-licensing)

 [Week 8](#week-8-analysing-acoustic-data)

 [Week 9](#week-9-extracting-data-from-audio)
## Week 1: Musical Datasets
I have identified Alessandro Amato as my particular artist of analysis for my project, and more specifically the song Adea. Audio recordings and metadata have been easy to find and are available on multiple websites. This sheet music was relatively easy to find thanks to IMSLP.org. This website provides digital notation music for the piano played in this song.
Here is an uploaded photo of the music that I transcribed. 

![Screenshot 2024-11-04 154014](https://github.com/user-attachments/assets/60f32c8d-99b3-438a-9f41-b425f03e7adc)
![Screenshot 2024-11-04 154202](https://github.com/user-attachments/assets/e370625e-df84-42d9-a72c-0f425f3623a2) 

### Task 3: Difficulties and challenges
Based on my experience earlier of attempting to work with music related data, I found it difficult particularly in the access aspect. This is more directed towards the musical sheets, as the other artists I was looked at, which were in bands as opposed to classical composers, could only be found on subscription and purchase-based websites. This makes the music harder to access, as I am requiring to pay in order to find the specific information I need. The current manifestations of data relate to this issue, as in a lot of cases data it is not as freely accessible as it should be. Individuals could face struggle in attempting to gather information which is being witheld from them due to profitability reasons and this is unfair. 

[Back to Weekly Task Tab](#each-weeks-tasks)


## Week 2: Using MuseScore
The OMR engine did not properly transcribe the time singatures. On the original sheet music they were set at 5/8, however MuseScore translated this as 3/4. Beat rests, articulations, tempos and row numbers have all been added to the sheet based on pure assumption. Separation of the notes have also changed. Essentially a whole different music piece has been created from the upload of my original sheet.

[Back to Weekly Task Tab](#each-weeks-tasks)

## Week 3: Music XML Files
The MusicXML file has a variety of different elements compared to the MEI files. For example the MusicXML file has over 600,000 characters as opposed to my MEI file which is at just 300,000 characters. The MEI files provide each note with an ID, unlike MusicXML. This would definitely be helpful if a musical sheet does not have a distinctive title. The rest element in MEI is also much more simple, only including a duration attribute on the same line, whereas the MusicXML file requires several lines for duration, voice and type. MEI files also keeps the note element on one single line with the attributes of dots, dur, oct, pname and stem.dir. MusicXML's note element however, is much more complicated, taking up multiple lines for each detail such as pitch, step, octave, duration, tie type, voice, type, dot default, stem, staff, beam number, notations and slur type. 

[Back to Weekly Task Tab](#each-weeks-tasks)


## Week 4: jSymbolic and Music21 
Task 1: Here were the results for my comparison of musical data in the sheet music Adea by Alessandro Amato and Right Here, Right Now by Fatboy Slim. 
![image](https://github.com/user-attachments/assets/7fa49a23-cefd-4ab4-a4b3-5a8d65389b17) 
Task 2: Here are the music data visualisations that I generated from inputting cell instructions to Music21 on Jupyter Notebooks.

![Image graph](https://github.com/user-attachments/assets/d6d9279a-f022-4798-a2a0-6f29175330db)
![ANother new image](https://github.com/user-attachments/assets/45d023d0-5ab3-43f8-a3d4-d0ccca63d700)
![new image 3](https://github.com/user-attachments/assets/53fe59a6-7aa5-46a7-8f96-291d572e0a1e)

[Back to Weekly Task Tab](#each-weeks-tasks)


## Week 5: Editing MEI Code
### Task 1: Create a metadata schema by listing 5 elements.

Chosen elements:

< Title

< Composer

< Publisher

< Address line 

< Price

Here is a link [to my meifriend file](https://raw.githubusercontent.com/dlambert8/MCA-2024/refs/heads/master/Adea%20by%20Allesandro%20Amato%20-%20copy-Part_1%20(1).mei) 

[Back to Weekly Task Tab](#each-weeks-tasks)


## Week 7: MEI Copyright Licensing
Here is a second version of my MEI file with the updated metadata. I have now added the metadata of genre classifications and a creative commons license, as we can see in the highlighted yellow. Once again here is the link to the mei file [I added this to](https://raw.githubusercontent.com/dlambert8/MCA-2024/refs/heads/master/Adea%20by%20Allesandro%20Amato%20-%20copy-Part_1%20(1).mei)

![mei friend photo](https://github.com/user-attachments/assets/5b1c86d0-f773-467a-86d3-f561ac8ef3fa)


In terms of genre classifications, I added the details of my genre as modern classical because my piece is of recent decades (2010s) yet is a piano piece with musical properties resembling classical music. I also believe the CC by 4.0 license is the most logical to choose as it accurately gives credit to me, as the creator of this MEI document, whilst also allowing other users to share and build upon the material. This can be seen once I copy the license agreement, where it states that reusers must give credit to the creator whilst allowing reusers to "distribute, remix, adapt, and build upon the material in any medium or format, even for commercial purposes." (Creative Commons, 2024). 

[Back to Weekly Task Tab](#each-weeks-tasks)


## Week 8: Analysing Acoustic Data
### Task 1: Creating a table for the pieces related to my theme
<table>  
<tr>  
<th>Title</th>
<th>Artist</th>  
<th>Composer</th>
<th>Copyright information</th>
<th>Genre</th>
<th>Source</th>
<th>File Format</th>
<th>Number of Channels</th>
<th>Sample Rate</th> 
<th>Bits Per Second</th>  
<th>Duration</th>  
</tr>

<tr> 
<td>Berceuse n. 3 Adea</td>
<td>Alessandro Amato</td>
<td>Alessandro Amato</td>
<td>	
Creative Commons Attribution Non-commercial No Derivatives 3.0 
</td>
<td>Classical/Piano</td>
<td>IMSLP</td>
<td>MP3</td>
<td>2</td>
<td>48000Hz</td> 
<td>128kbps</td>
<td>5 minutes 53 seconds</td>  
</tr>

<tr> 
<td>Für Elise, WoO 59</td>
<td>Lev Kitkin</td>
<td>Ludwig van Beethoven</td>
<td>	
Creative Commons Attribution 4.0 
</td>
<td>Classical/Bagatelles/Piano</td>
<td>IMSLP</td>
<td>FLAC</td>
<td>2</td> 
<td>96000Hz</td>  
<td>1472kbps</td> 
<td>3 minutes 18 seconds</td>  
</tr>

<tr> 
<td>Piano Sonata No.14, Op.27 No.2</td>
<td>Luis Kolodin</td>
<td>Ludwig van Beethoven</td>
<td>Creative Commons Attribution-ShareAlike 4.0</td>
<td>Classical/Sonata/Piano</td>
<td>IMSLP</td>
<td>MP3</td>
<td>2</td>
<td>44100Hz</td>
<td>128kbps</td>
<td>5 minutes 57 seconds</td>  
</tr>
</table>

### Task 2: Here are the waveforms and the spectograms for my pieces.

Below me is the waveform-based analysis on Berceuse n. 3 Adea by Alessandro Amato.

![Screenshot 2024-11-15 020800](https://github.com/user-attachments/assets/d9872432-35d1-4ea6-8458-dcee52f1ac38)

Below me here is the time-frequency analysis spectogram for Berceuse n. 3 Adea by Alessandro Amato.

![Screenshot 2024-11-15 021306](https://github.com/user-attachments/assets/173149c6-c0d5-48df-b373-199e702036ad)

Below me here is the waveform-based analysis for Für Elise, WoO 59 by Ludwig van Beethoven.

![Screenshot 2024-11-15 022342](https://github.com/user-attachments/assets/0bb5e42e-5f5c-4a5f-9da0-c96a172dbd7d)

Below me here is the time-frequency analysis spectogram for Für Elise, WoO 59 by Ludwig van Beethoven.

![Screenshot 2024-11-15 022415](https://github.com/user-attachments/assets/ce4569da-fcc1-41f4-a428-f22f72b5f53d)

Below me is the waveform-based analysis on Piano Sonata No.14, Op.27 No.2 by Ludwig van Beethoven.

![Screenshot 2024-11-15 023821](https://github.com/user-attachments/assets/458db3ae-4681-483f-98a8-9511bd399457)

Below me is the time-frequency analysis on Piano Sonata No.14, Op.27 No.2 by Ludwig van Beethoven.

![Screenshot 2024-11-15 023841](https://github.com/user-attachments/assets/9bcb2637-d67b-41f1-b019-a6c302548ce8)

One key advantage that time frequency analysis has over a waveform-based analysis is that sounds are analysed as individual components. We can observe this specifically on the spectrograms for Piano Sonata No.14, Op.27 No.2 by Ludwig van Beethoven. As multiple notes are played on the piano throughout this song, the spectrogram individually captures each note and is represented through multiple colours. On the other hand, the waveform-based analysis only captures noise collectively and doesn’t distinguish between individual instruments and notes. As a result, the music data which can be understood from a time frequency analysis is much more detailed.

[Back to Weekly Task Tab](#each-weeks-tasks)


## Week 9: Extracting data from audio

### Task 1: Generating spectograms, MFCCs and chromagrams from SonicVisualiser.

Spectogram for Berceuse n. 3 Adea by Alessandro Amato.

![Screenshot 2024-11-21 102920](https://github.com/user-attachments/assets/ab7f6056-ec04-42cf-949c-9e2e6d05279d)

Mel Frequency Cepstral Coefficients for Berceuse n. 3 Adea by Alessandro Amato.

![Screenshot 2024-11-21 102945](https://github.com/user-attachments/assets/430d700b-2944-4645-a808-ebb55e5cb3c3)

Chromagram for Berceuse n. 3 Adea by Alessandro Amato.

![adea](https://github.com/user-attachments/assets/5bfb81f6-452c-4e3a-8140-acbf5c094d20)

Spectogram for Für Elise, WoO 59 by Ludwig van Beethoven.

![fur elise 3](https://github.com/user-attachments/assets/a7eced66-addc-41cb-b960-5632c87ae35c)


Mel Frequency Cepstral Coefficients for Für Elise, WoO 59 by Ludwig van Beethoven.

![Fur elise](https://github.com/user-attachments/assets/3e0c5c3e-b7fc-486f-95f6-8b229aac4248)


Chromagram for Für Elise, WoO 59 by Ludwig van Beethoven.

![fur elise (2)](https://github.com/user-attachments/assets/63a81f1a-c46b-4d96-b7e4-11c9138049e1)


Spectogram for Moonlight Sonata Except by Ludwig van Beethoven

![moonlight (2)](https://github.com/user-attachments/assets/03c20680-d342-423e-9a9e-c088b5cfc7ff)

Mel Frequency Cepstral Coefficients for Moonlight Sonata Except by Ludwig van Beethoven

![moonlight](https://github.com/user-attachments/assets/a09c5692-44d1-40fd-ba94-33b45afb812d)

Chromagram for Piano Sonata No.14, Op.27 No.2 by Ludwig van Beethoven.

![Screenshot 2024-11-21 103925](https://github.com/user-attachments/assets/bbbc5b1c-d4a1-4bdc-806b-a34bcb259ab2)

### Task 2: Histogram Comparisons for MFCC of 3 chosen tracks

#### Chromagrams:


[1. Adea](https://github.com/dlambert8/MCA-2024/blob/master/adeachroma.ipynb) 

[2. Moonlight Sonata](https://github.com/dlambert8/MCA-2024/blob/master/moonlightchroma%20(1).ipynb)

[3. Flight FM](https://github.com/dlambert8/MCA-2024/blob/master/flightfmchroma.ipynb)

#### Mel Frequency Cepstral Coefficients:


[1. Adea](https://github.com/dlambert8/MCA-2024/blob/master/adea_melfrequency.ipynb)

[2. Moonlight Sonata](https://github.com/dlambert8/MCA-2024/blob/master/moonlight_melfrequency.ipynb)

[3. Flight FM](https://github.com/dlambert8/MCA-2024/blob/master/flightfm.ipynb)



#### Spectograms:


[1. Adea](https://github.com/dlambert8/MCA-2024/blob/master/adeaspectogram.ipynb)

[2. Moonlight Sonata](https://github.com/dlambert8/MCA-2024/blob/master/moonlightspectogram.ipynb)

[3. Flight FM](https://github.com/dlambert8/MCA-2024/blob/master/flightfmspectogram.ipynb)


