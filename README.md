# Thought 2 Speech
Towards an Brain-Computer Interface for Imagined Speech Classification via EEG signals.
## Phase 1 : Experiment Design and Dataset Generation
Signals are recorded via the [EMOTIV EPOC X Headset](https://www.emotiv.com/epoc-x/), a 14 - channel wireless EEG headset.

### Background Reading
- [Decoding Covert Speech From EEG-A Comprehensive Review (2021)](https://www.frontiersin.org/articles/10.3389/fnins.2021.642251/full)
- [Thinking out loud, an open-access EEG-based BCI dataset for inner speech recognition (2022)](https://www.nature.com/articles/s41597-022-01147-2)
- [Effect of Spoken Speech in Decoding Imagined Speech from Non-Invasive Human Brain Signals (2022)](https://arxiv.org/abs/2212.02047)

#### A guide for beginners
PsychoPy® allows both *GUI* *first* and *Code* *first* approaches to designing and running experiments via a *Builder view* and *Coder view* respectively. Follow the steps below to run the experiment defined here.


##### 1. Install PsychoPy®. [**Reference**](https://www.psychopy.org/download.html#pip-install)
We recommend the standalone version (64 Bit Windows) - the installation is seamless. 
###### Standalone Version (64 Bit Windows)

&nbsp;&nbsp;&nbsp;&nbsp;This installation pathway enables you to work with both the Builder and Coder views concurrently. Creates a PsychoPy® environment with &nbsp;&nbsp;&nbsp;&nbsp;Python 3.8.10.


###### Anaconda and Miniconda
&nbsp;&nbsp;&nbsp;&nbsp;Intended for more technical users. This installation pathway invloves an [environment file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/psychopy-env.yml) that can be used to install PsychoPy® and its &nbsp;&nbsp;&nbsp;&nbsp;dependencies. 

&nbsp;&nbsp;&nbsp;&nbsp;**Note:** This method creates bugs at present and is unusable. Working on a fix. [13/12/2022] 

 
##### 2. Begin the Experiment.
To run the experiment via a **local IDE**, simply execute the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) after choosing the appropriate environment.

To run the experiment via the **native PsychoPy® IDE**, save the [Stimulus file](https://github.com/armaanchowfin/Thought2Speech/blob/main/Experiment%20Protocol%20-%20Pyschopy/stimuli_psycho.py) to the PsychoPy® experiment directory and execute as usual from within PsychoPy®.

## Phase 2 : Data Analysis and Classification
The imprecise nature of EEG hardware makes the subsequent data analysis critical.

### Background Reading
- [Transfer learning for medical image classification: a literature review (2022)](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-022-00793-7)
- [Capsule Networks: A Quick Primer (2020)](https://blog.paperspace.com/capsule-networks/)
- 
