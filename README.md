# Thought 2 Speech
Towards an Brain-Computer Interface for Imagined Speech Classification via EEG signals.
## Phase 1 : Experiment Design and Dataset Generation
Signals are recorded via the [EMOTIV EPOC X Headset](https://www.emotiv.com/epoc-x/), a 14 - channel wireless EEG headset.

### Background Reading
- [Thinking out loud, an open-access EEG-based BCI dataset for inner speech recognition](https://www.nature.com/articles/s41597-022-01147-2)
- [Effect of Spoken Speech in Decoding Imagined Speech from Non-Invasive Human Brain Signals](https://arxiv.org/abs/2212.02047)

#### A guide for beginners
PsychoPy® allows both *GUI* *first* and *Code* *first* approaches to designing and running experiments via a *Builder view* and *Coder view* respectively. Follow the steps below to run the experiment defined here.


##### 1. Install PsychoPy®. [**Reference**](https://www.psychopy.org/download.html#pip-install)
We recommend the standalone version (64 Bit Windows) - the installation is seamless. 
###### Standalone Version (64 Bit Windows)

&nbsp;&nbsp;&nbsp;&nbsp;This installation pathway enables you to work with both the Builder and Coder views concurrently. Creates a Pyschopy environment with &nbsp;&nbsp;&nbsp;&nbsp;Python 3.8.10.

&nbsp;&nbsp;&nbsp;&nbsp;[Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) can be run in the native PsychoPy® IDE **or** in a local IDE after choosing the appropriate environment.


###### Anaconda and Miniconda
&nbsp;&nbsp;&nbsp;&nbsp;Intended for more technical users. This installation pathway invloves an [environment file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/psychopy-env.yml) that can be used to install PsychoPy® and its &nbsp;&nbsp;&nbsp;&nbsp;dependencies. 

&nbsp;&nbsp;&nbsp;&nbsp;**Note:** This method creates bugs at present and is unusable. Working on a fix. [13/12/2022] 

 
##### 2. Begin the Experiment.
To perform the experiment via a **local IDE**, simply run the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) after choosing the appropriate environment.

To perform the experiment via the **native PsychoPy® IDE**, save the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) in the experiment directory and execute as usual from within PsychoPy®.

## Phase 2 : Data Analysis and Classification
