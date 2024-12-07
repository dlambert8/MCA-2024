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
(Note: I had to edit out Für Elise, WoO 59 by Ludwig van Beethoven for Flight FM by Joy Orbison because the audio had randomly corrupted an was no longer working.)
#### Chromagrams:


[1. Adea](https://github.com/dlambert8/MCA-2024/blob/master/adeachroma%20(3).ipynb) 

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


The first histogram captures differences in the sound produced through a graph similar to a heatmap. As my third track is a modern electronic techno song, it has much more than just one instrument playing at once. This is stark in contrast to the other two songs, which are both piano pieces. The second graph, which captures single features, similarly captures the similarity with both piano pieces and a difference with the third piece. The third piece reaches much higher peaks at common frequency. I’m assuming this is the average volume of the song, which would make sense, as it uses loud synthesisers throughout. The third bar graph, which also captures single features, shows a clear difference between the songs. Each song’s graph experiences high points and low points at individual times and periods. The third piece once more is the easiest to distinguish, as the lines on the chart are slightly chunkier. I believe that this would again be due to the multiple instruments and sounds playing at once. The final graph is the one that shows the most significant differences between the songs. This is due to the 19 small bar graphs that display audio patterns during the respective songs. Each pattern in these graphs is clear in its contrast to the other. Overall, these graphs met my expectations, as the two songs, Adea by Alessandro Amato and Moonlight by Ludwig Beethoven, are both classical piano pieces and share the most common similarities, whereas Flight FM is a modern electronic techno song and shares the most differences between the two.



[Back to Weekly Task Tab](README.md)
