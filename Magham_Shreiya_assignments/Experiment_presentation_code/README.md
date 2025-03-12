# Experiment Presentation Code: Human Face Stimulus Valence Study

### **Experiment Overview**: 
> #### The effect of the interaction between eyebrow diagonality and cartoonization of negative-affect facial image stimuli on valence perception

Although the title of this web-based study is wordy, it is actually very simple. This experiment manipulates:

(1) the **diagonality** of the eyebrows (i.e., the angle from vertical the eyebrows make, with the vertex of these two lines pointing downwards. Think of diagonality as the extent to which your eyebrows are furrowed or knitted together), and

(2) the **cartoonization** (i.e., whether images are realistic or rendered in cartoon style)

of negative-affect (or emotionally negative) facial image stimuli. Then, we will be able to look at the effect of the *interaction* between these two factors on the dependent variable of the participants' perceived emotional valence from the stimuli (i.e., how emotionally negative vs. positive the stimuli seem to them). The dependent variable will be rated on a scale of 1 to 7, with *1 indicating an extremely negative perceived valence*, and *7 indicating an extremely positive perceived valence*.

The study has a two-factor, *within-participants* design, and all participants will be required to rate the perceived emotional valence for each stimulus. The order of these stimuli (prior to creating the 2 blocks of trials) was randomized to prevent order effects. Valence will be rated on a scale of 1 to 7 because it is commensurate with the scale used by the *OASIS* (Open Affective Standard Image Set) database created by Kurdi et al. (2017), which is where the original stimuli for this study are derived from.

> #### Components of the experiment

(1) Welcome message

(2) Overview of study

(3) Ethics and consent

(4) Instructions

(5) Demo trials

(6) Block 1 of the experiment (15 trials)

(7) Inter-block interval (2-minute break)

(8) Block 2 of the experiment (15 trials)

(9) Debrief and thank you pages


*Note:* These are essentially the trials that you will find within the experiment code html file. To get to this file, use the following pathway: maghamShreiya \> Magham_Shreiya_assignments \> Experiment_presentation_code
\> Experiment_presentation_code_working.html.


### **Important Folders and Files in the 'Experiment_presentation_code' Folder within the 'maghamShreiya' Repository:**

(1) **jspsych**: This folder contains downloaded/imported jsPsych
    library scripts. It is crucial that the name of this folder and 
    Experiment_presentation_code_working.html are congruent. This folder 
    must be downloaded prior to running the experiment code html file in
    your browser. 
    
(2) **stimuli**: This folder contains the stimulus images for this study. It
    contains the sub-folders with stimuli from the different conditions. These
    experimental conditions include: 
    
      (a) a realistic facial image stimulus control condition (i.e., the images are taken 
      right from the OASIS database.) Stimuli from the database were excluded if they did 
      not contain a singular, human face, included children (for ethical reasons around 
      using AI programs for manipulating their facial features), were positive in affect 
      (according to Russell's (1980) circumplex model of affect; this was determined based
      on the nomenclature of stimuli in the OASIS database), or if not all facial features 
      were included in the stimulus. This condition corresponds to the sub-folder 
      'oasisControl' in 'oasisStimuli'. n = 5. 
      
      (b) a cartoon facial image stimulus condition, with no manipulations to eyebrow diagonality. For cartoonifying the 5 realistic image stimuli from the OASIS database, I used the 'Cartoon1' effect on Picsart, with a fade of 50. This condition corresponds to the sub-folder 'cartoonControl' in 'cartoonStimuli'. n = 5.
      
      (c) a realistic facial image stimulus, 55 degrees from vertical eyebrow diagonality condition. n = 5.
      
      (d) a cartoon facial image stimulus, 55 degrees from vertical eyebrow diagonality condition. n = 5.  
      
      (e) a realistic facial image stimulus, 45 degrees from vertical eyebrow diagonality condition. n = 5.  
      
      (f) a cartoon facial image stimulus, 45 degrees from vertical eyebrow diagonality condition. n = 5.

      There is also a sub-folder under the 'oasisStimuli' folder that is entitled     
      'oasisDemo.' These images will be used for the demo trials to get participants 
      familiar with how the experiment will run prior to the actual trials starting. n = 2.

(3) **README.md**: Lastly, there is this README.md file that you're
    currently viewing. This file helps viewers understand the critical
    elements to making the code for the Experiment_presentation_code_working.html 
    file run.

### **Steps for running and/or viewing the experiment presentation code for this study:**

(1) Download all the files and folders necessary (see above) to your
    local computer. This includes **ALL** of the contents within the
    ' Experiment_presentation_code' folder (access this folder through the pathway
    'maghamShreiya \> Magham_Shreiya_assignments \>  Experiment_presentation_code'). 
    Alternatively, you can clone the entire repository (maghamShreiya) to your local 
    computer using the 'git clone' function.

(2) Click on the Experiment_presentation_code_working.html file. The experiment
    will open up in your web browser.

(3) If you'd like to view the code, open the Experiment_presentation_code_working.html file     in your preferred IDE.
