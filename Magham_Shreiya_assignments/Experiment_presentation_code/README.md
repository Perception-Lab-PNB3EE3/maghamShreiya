# Experiment Presentation Code: *Caricature Valence Study*

<details>

-   [Experiment Overview](#experiment-overview)
-   [Important Folders and Files in the Experiment_presentation_code Folder](#important-folders-and-files-in-the-experiment_presentation_code-folder)
-   [Significance of Study](#significance-of-study)
-   [Running and Viewing Experiment Presentation Code](#steps-for-running-and-viewing-the-experiment-presentation-code)
-   [References](#references)

</details>

### **Experiment Overview** 
> #### The effect of the interaction between eyebrow diagonality and cartoonization of negative-affect facial image stimuli on valence perception

Although the title of this web-based study is wordy, it is very simple. This experiment manipulates:

(1) the **diagonality** of the eyebrows (i.e., the angle from vertical the eyebrows make, with the vertex of these two lines pointing downwards. Think of diagonality as the extent to which your eyebrows are furrowed or knitted together), and

(2) the **cartoonization** (i.e., whether images are realistic or rendered in cartoon style)
of negative-affect (or emotionally negative) facial image stimuli. Then, we will be able to look at the effect of the *interaction* between these two factors on the dependent variable of the participants' perceived emotional valence from the stimuli (i.e., how emotionally negative vs. positive the stimuli seem to them). The dependent variable will be rated on a slider scale that ranges from *extremely negative* to *extremely positive*.

The study has a 2x2, *within-participants* design, and all participants will be required to rate the perceived emotional valence for each stimulus. The order of these stimuli (prior to creating the 2 blocks of trials) was randomized to prevent order effects. These stimuli from the 4 conditions (see 'stimuli' under the [below](#important-folders-and-files-in-the-experiment_presentation_code-folder) section) will be interspersed with filler images that participants will also rate, to prevent people from getting similar looking stimuli in succession (which could bias responses) and prevent gambler's fallacy-like effects that might arise from rating solely negative image stimuli.

> #### Components of the experiment

(1) Welcome message

(2) Overview of study

(3) Ethics and consent

(4) Instructions

(5) Demo trials (2 images)

(6) Block 1 of the experiment (20 trials)

(7) Inter-block interval (30-second break)

(8) Block 2 of the experiment (20 trials)

(9) Debrief and thank you pages


*Note:* These are essentially the trials that you will find within the experiment code html file. 
To get to this file, use the following pathway: 'maghamShreiya' \> 'Magham_Shreiya_assignments' 
\> 'Experiment_presentation_code' \> 'Experiment_presentation_code_assignment.html'.


### **Important Folders and Files in the 'Experiment_presentation_code' Folder**

(1) **jspsych**: This folder contains downloaded/imported jsPsych
    library scripts. It is crucial that the name of this folder and 
    'Experiment_presentation_code_assignment.html' are congruent. This folder 
    must be downloaded prior to running the experiment code html file in
    your browser. 
    
(2) **stimuli**: This folder contains the stimulus images for this study. It
    contains the sub-folders with stimuli from 4 different conditions. These
    experimental conditions include: 
    
  (a) a realistic facial image stimulus control condition (RC condition). For 
  this condition, the images were taken right from the OASIS database. Stimuli 
  from the database were excluded if they did not contain a singular, human face, 
  included children (for ethical reasons around using software for manipulating 
  their facial features), were positive in affect (according to [Russell's (1980)](#references) 
  circumplex model of affect; this was determined based on the nomenclature 
  of stimuli in the OASIS database), or if any facial features were obstructed in
  the image. This condition corresponds to the sub-folder 'oasisControl' 
  in 'oasisStimuli'. *n* = 5. 
      
  (b) a cartoon facial image stimulus condition, with no manipulations to eyebrow 
  diagonality (CC condition). For cartoonifying the 5 realistic image stimuli 
  from the OASIS database, the 'Cartoon1' effect on Picsart was used, with a fade 
  of 50. This condition corresponds to the sub-folder 'cartoonControl' in 'cartoonStimuli'.
  *n* = 5.
      
  (c) a realistic facial image stimulus condition, with a 50-degrees-from-vertical eyebrow 
  diagonality manipulation (RE condition). This manipulation on the realistic images from the 
  OASIS database was done using 'ibisPaint' with the 'lasso' and 'tranform' tools for 
  manipulating the angle of the eyebrows. Empty spaces were filled in with the 'Soft Pastel' 
  brush at 30% opacity. Angles were measured using a protractor. This condition corresponds 
  to the sub-folder 'oasisEyebrow' in 'oasisStimuli.' *n* = 5.
      
  (d) a realistic facial image stimulus condition, with a 50-degrees-from-vertical eyebrow 
  diagonality manipulation (CE condition). This manipulation on images from the OASIS 
  database that were cartoonized was done using 'ibisPaint' (same procedure as the 
  RE condition). This condition corresponds to the sub-folder 'cartoonEyebrow' in 
  'cartoonStimuli.' *n* = 5.  
      
  There is also a sub-folder under the 'oasisStimuli' folder that is entitled 'oasisDemo' containing 2 images. These images will be used for the demo trials 
  to get participants familiar with how the experiment will run prior to the actual trials starting. *n* = 2.
      
  Another sub-folder under the 'stimuli' folder includes 'fillerImages,' which were taken 
  from the OASIS database directly, as well as cartoonized. The affect of the images in this
  folder range from negative to positive, and contain only images containing singular 
  human faces, as well as no children. Some of the images that were rejected from the main stimuli 
  for the 4 conditions for having obstructed facial features were included as filler images.
  *n* = 20.

(3) **README.md**: Lastly, there is this README.md file that you're
    currently viewing. This file helps viewers understand the critical
    elements to making the code for the 'Experiment_presentation_code_assignment.html'
    file run.
    
    
### **Significance of Study**
Exaggarated features and cartoonization are key components of the artistic technique 
called **caricaturization**. It is important that we better understand the effect of 
caricaturization on our perceptions of emotional valence because caricaturization 
is used for conveying highly influential messages (i.e., in the case of political 
cartoons). 

Since caricaturization is often used to convey messages that are negative in nature, 
in this experiment, I manipulated the eyebrow diagonality and cartoonization of negative-affect 
images of human faces. 

### **Steps for running and viewing the experiment presentation code**

(1) Download all the files and folders necessary (see [above](#important-folders-and-files-in-the-experiment_presentation_code-folder)) to your local computer. 
    This includes **ALL** of the contents within the 'Experiment_presentation_code' folder (access this 
    folder through the pathway 'maghamShreiya' \> 'Magham_Shreiya_assignments' \> 'Experiment_presentation_code'). 
    Alternatively, you can clone the entire repository (maghamShreiya) to your local computer using the 'git clone' function.

(2) Click on the 'Experiment_presentation_code_assignment.html' file. The experiment
    will open up in your web browser.

(3) If you'd like to view the code, open the 'Experiment_presentation_code_assignment.html' 
    file in your preferred IDE.
    
### **References**
Russell, J. A. (1980). A circumplex model of affect. *Journal of personality and social psychology*, 
    *39*(6), 1161-1178. https://doi.org/10.1037/h0077714