# Capstone Project - Bacteria classification

## Dataset
The dataset consists of 'jpeg' pictures of bacteria colonies collected from soil samples on 10 different locations (referred to as locations C1-C10) in various parks in Manhattan. Pictures correspond to scanned images of Petri dishes cotaining the bacteria colonies, captured by Epson scanner at resolution ranging from 400 to 3200 dpi.  

Data was organized on different folders corresponding to 3 different types of images taken at 8 different times, explained as follows:

- Type “Serial” corresponds to images of a single petri dish containing well-separated colonies of the same bacteria species but at 9 different concentrations, which were allowed to grow over time.

- Type “Control” corresponds to images where a single drop of a bacteria species was dropped in the petri dish at a specific concentration (instead of 9 different concentrations like in the case of “Serial” type). This was done with the purpose of checking if having several colonies in the same petri dish has any influence in the growing patterns vs having a single colony so the algorithm could learn from both situations.

- Type “Streak” corresponds to multiple drops but is where the streaks (linear pattern) is drawn across the petri dish with pipettes with different concentrations.

For each of the 3 types described above, images were taken during 4 different days, 2 collections each day (AM and PM, 12 hours apart), for a total of 8 different timestamps. This will be useful for the bacteria classification model to learn different patterns of colonies form the same species, over different growing times.

Colonies for each location were classified using conventional time-consuming classification methods and they were found 7 different bacterial species. It was found that locations 'C2' and 'C3' correspond to the same bacterial species, same that locations 'C4' and 'C7', as well as locations 'C8' and 'C10'.

Timestamps, locations and image type are included within each image filename. As example, '7-10_PM_P1C1_Serial.jpg' correponds to a image taken on 7/10 during PM hours, location 'C1', image type Serial. 

Additional images of petri dishes from different species on the same plate will be provided later for model testing purposes (goal is to classify these).

Training images can be downloaded from this [link](https://drive.google.com/open?id=116Iu8uSJcEYCIJd5cMJmms9B-bvQ5AG4) (200 images, about 100MB size).
