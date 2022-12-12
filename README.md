# Thought 2 Speech
Towards an Brain-Computer Interface for Imagined Speech Classification via EEG. 
## Phase 1 : Experiment Design and Dataset Generation
Signals are recorded via the [EMOTIV EPOC X Headset](https://www.emotiv.com/epoc-x/), a wireless headset with 14 channels.

### Background Reading
1. [Thinking out loud, an open-access EEG-based BCI dataset for inner speech recognition](https://www.nature.com/articles/s41597-022-01147-2)

### Usage
Psychopy allows both *GUI* *first* and *Code* *first* approaches to designing and running experiments via a *Builder view* and *Coder view* respectively.


##### 1. Install Psychopy. [**Reference**](https://www.psychopy.org/download.html#pip-install)
&nbsp;&nbsp;&nbsp;&nbsp;For beginners, we recommend installing the standalone version, enabling you to work with both the Builder and Coder views concurrently.

&nbsp;&nbsp;&nbsp;&nbsp;Create a Psychopy virtual environment via the [environment file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/psychopy-env.yml) provided in this repo. This prevents various dependency conflicts. 
##### 2. Begin the Experiment.
&nbsp;&nbsp;&nbsp;&nbsp; Run the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) in your IDE.

## Phase 2 : Data Analysis and Classification
