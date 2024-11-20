# Music Curation Project
| [Week 1: Musical Datasets](#week-1-musical-datasets) |
## Week 1: Musical Datasets
I have identified Allesandro Amato as my particular artist of analysis for my project, and more specifically the song Adea. Audio recordings and metadata have been easy to find and are available on multiple websites. This sheet music was relatively easy to find thanks to IMSLP.org. This website provides digital notation music for the piano played in this song.
Here is an uploaded photo of the music that I transcribed.

![Screenshot 2024-11-04 154014](https://github.com/user-attachments/assets/60f32c8d-99b3-438a-9f41-b425f03e7adc)
![Screenshot 2024-11-04 154202](https://github.com/user-attachments/assets/e370625e-df84-42d9-a72c-0f425f3623a2) 

Task 3: Based on my experience earlier of attempting to work with music related data, I found it difficult particularly in the access aspect. This is more directed towards the musical sheets, as the other artists I was looked at, which were in bands as opposed to classical composers, could only be found on subscription and purchase-based websites. This makes the music harder to access, as I am requiring to pay in order to find the specific information I need. The current manifestations of data relate to this issue, as in a lot of cases data it is not as freely accessible as it should be. Individuals could face struggle in attempting to gather information which is being witheld from them due to profitability reasons and this is unfair.
## Week 2: Using MuseScore
The OMR engine did not properly transcribe the time singatures. On the original sheet music they were set at 5/8, however MuseScore translated this as 3/4. Beat rests, articulations, tempos and row numbers have all been added to the sheet based on pure assumption. Separation of the notes have also changed. Essentially a whole different music piece has been created from the upload of my original sheet.
## Week 3: Music XML Files
The MusicXML file has a variety of different elements compared to the MEI files. For example the MusicXML file has over 600,000 characters as opposed to my MEI file which is at just 300,000 characters. The MEI files provide each note with an ID, unlike MusicXML. This would definitely be helpful if a musical sheet does not have a distinctive title. The rest element in MEI is also much more simple, only including a duration attribute on the same line, whereas the MusicXML file requires several lines for duration, voice and type. MEI files also keeps the note element on one single line with the attributes of dots, dur, oct, pname and stem.dir. MusicXML's note element however, is much more complicated, taking up multiple lines for each detail such as pitch, step, octave, duration, tie type, voice, type, dot default, stem, staff, beam number, notations and slur type.
## Week 4: jSymbolic and Music21 
Task 1: Here were the results for my comparison of musical data in the sheet music Adea by Alessandro Amato and Right Here, Right Now by Fatboy Slim. 
![image](https://github.com/user-attachments/assets/7fa49a23-cefd-4ab4-a4b3-5a8d65389b17)
Task 2: Here are the music data visualisations that I generated from inputting cell instructions to Music21 on Jupyter Notebooks.

![Image graph](https://github.com/user-attachments/assets/d6d9279a-f022-4798-a2a0-6f29175330db)
![ANother new image](https://github.com/user-attachments/assets/45d023d0-5ab3-43f8-a3d4-d0ccca63d700)
![new image 3](https://github.com/user-attachments/assets/53fe59a6-7aa5-46a7-8f96-291d572e0a1e)

## Week 5: Editing MEI Code
Task 1: Create a metadata schema by listing 5 elements

Chosen elements:

< Title

< Composer

< Publisher

< Address line 

< Price

Here is a link [to my meifriend file](https://raw.githubusercontent.com/dlambert8/MCA-2024/refs/heads/master/Adea%20by%20Allesandro%20Amato%20-%20copy-Part_1%20(1).mei) 





## Week 7: MEI Copyright Licensing
Here is a second version of my MEI file with the updated metadata. I have now added the metadata of genre classifications and a creative commons license, as we can see in the highlighted yellow. Once again here is the link to the mei file [I added this to](https://raw.githubusercontent.com/dlambert8/MCA-2024/refs/heads/master/Adea%20by%20Allesandro%20Amato%20-%20copy-Part_1%20(1).mei)

![mei friend photo](https://github.com/user-attachments/assets/5b1c86d0-f773-467a-86d3-f561ac8ef3fa)


In terms of genre classifications, I added the details of my genre as modern classical because my piece is of recent decades (2010s) yet is a piano piece with musical properties resembling classical music. I also believe the CC by 4.0 license is the most logical to choose as it accurately gives credit to me, as the creator of this MEI document, whilst also allowing other users to share and build upon the material. This can be seen once I copy the license agreement, where it states that reusers must give credit to the creator whilst allowing reusers to "distribute, remix, adapt, and build upon the material in any medium or format, even for commercial purposes." (Creative Commons, 2024). 

# Week 8: Analysing Acoustic Data
Task 1: Creating a table for the pieces related to my theme
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

Task 2: Here are the waveforms and the spectograms for my pieces  

Waveforms and spectogram for Berceuse n. 3 Adea by Alessandro Amato

![Screenshot 2024-11-15 020800](https://github.com/user-attachments/assets/d9872432-35d1-4ea6-8458-dcee52f1ac38)

![Screenshot 2024-11-15 021306](https://github.com/user-attachments/assets/173149c6-c0d5-48df-b373-199e702036ad)

Waveforms and spectogram for Für Elise, WoO 59 by Ludwig van Beethoven

![Screenshot 2024-11-15 022342](https://github.com/user-attachments/assets/0bb5e42e-5f5c-4a5f-9da0-c96a172dbd7d)

![Screenshot 2024-11-15 022415](https://github.com/user-attachments/assets/ce4569da-fcc1-41f4-a428-f22f72b5f53d)

Waveforms and spectogram for Piano Sonata No.14, Op.27 No.2 by Ludwig van Beethoven

![Screenshot 2024-11-15 023821](https://github.com/user-attachments/assets/458db3ae-4681-483f-98a8-9511bd399457)

![Screenshot 2024-11-15 023841](https://github.com/user-attachments/assets/9bcb2637-d67b-41f1-b019-a6c302548ce8)
