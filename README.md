# Thought 2 Speech
Towards an Brain-Computer Interface for Imagined Speech Classification via EEG. 
## Phase 1 : Experiment Design and Dataset Generation
Signals are recorded via the [EMOTIV EPOC X Headset](https://www.emotiv.com/epoc-x/), a wireless headset with 14 channels.

### Background Reading
1. [Thinking out loud, an open-access EEG-based BCI dataset for inner speech recognition](https://www.nature.com/articles/s41597-022-01147-2)

### Usage
PsychoPy® allows both *GUI* *first* and *Code* *first* approaches to designing and running experiments via a *Builder view* and *Coder view* respectively.


#### 1. Install PsychoPy®. [**Reference**](https://www.psychopy.org/download.html#pip-install)
We recommend the standalone version (64 Bit Windows) - the installation is seamless. 
##### Standalone Version (64 Bit Windows)

&nbsp;&nbsp;&nbsp;&nbsp;This installation pathway enables you to work with both the Builder and Coder views concurrently. Uses Python 3.8.10.

&nbsp;&nbsp;&nbsp;&nbsp;To perform the experiment via a local IDE, simply run the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py), choosing the interpreter installed with the standalone installer.

##### Anaconda and Miniconda
&nbsp;&nbsp;&nbsp;&nbsp;Intended for more technical users. This installation pathway invloves an [environment file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/psychopy-env.yml) that can be used to install PsychoPy® and its &nbsp;&nbsp;&nbsp;&nbsp;dependencies. 

&nbsp;&nbsp;&nbsp;&nbsp;**Note:** This pathway creates bugs at present and is unusable. [13/12/2022] 

 
#### 2. Begin the Experiment.
&nbsp;&nbsp;&nbsp;&nbsp; Run the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) in your IDE.

## Phase 2 : Data Analysis and Classification
