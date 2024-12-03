# NLP & ADAS

## Hello

Thank you for your interest and visiting my page! 
I am mainly interested in optimizing general everyday tasks which led me to NLP(Natural Language Processing) and ADAS(Autonomous Driving Assitance Systems) for which I have done close to industry level projects. And would like to work in motion planning for cars/mobile robots OR NLP systems (RAG,LLMOps) in health care branche. Below you can find a mix of personal, bachelor/master programm related and independant research projects I have done so far :) 



## Projects

- TRADE: [HackaTUM24: Optiver Challenge (Finalist)](#hackatum24-optiver-challenge-finalist)
- NLP:   [Developing Systems for Trustworthy Medical Question Answering*](#developing-systems-for-trustworthy-medical-question-answering-ongoing)
- ADAS:  [Open-Loop Baseline for Reinforcement Learning Locomotion Tasks](#open-loop-baseline-for-reinforcement-learning-locomotion-tasks)
- NLP:   [Obsidian Live Text Translator from German/Turkish to English](#obsidian-plugin---live-text-translator-from-germanturkish-to-english)
- ADAS:  [Trajectory Planning in Dynamic Environments*](#trajectory-planning-in-dynamic-environments)
- NLP:   [Debate Clustering*](#debate-clustering)
- NLP:   [Echo Canyon: Lyric Generator incl. Rhyming Tool*](#echo-canyon-lyric-generator-incl-rhyming-tool)
- ADAS:  [Route Prediction in Roundabout with Neural Networks utilizing Prior Map Information](#route-prediction-in-roundabout-with-neural-networks-utilizing-prior-map-information)

*incl. code on GitHub

---


### HackaTUM24: Optiver Challenge (Finalist)
Optiver Holding B.V. is a proprietary trading firm and market maker for various exchange-listed financial instruments.
Our strategy for the challenge was mainly a Real-time fourier decomposition for black box approximation of other market agents.
Team Role: market strategizer, facilitator, line by line code reviewer, bug finder    
More info here: [Devpost Page](https://devpost.com/software/seismicspecialists?ref_content=my-projects-tab&ref_feature=my_projects), 
[LinkedIn Post & Certificate](https://www.linkedin.com/feed/update/urn:li:activity:7269360890720698371/)

Simulation example of the first part of the final round:
<video width="480" height="460" controls loop="" muted = "" autoplay="">
    <source src="https://tatlikazan-rv.github.io/assets/files/hackatum-optiver/trade-algo-sim.mp4">
</video>



### Developing Systems for Trustworthy Medical Question Answering

I have developed a local-hosted (opt. cloud-hosted) Perplexity like Generative AI(NLP-RAG) app for medical research/consumer questions, based on scientific articles. It focuses on privacy and interpretability. It can handle 20 million research papers.

UI Example for Model/Method Comparisons:

<img src="https://tatlikazan-rv.github.io/assets/files/tMQA/ScreenRecMT.gif">


Pipeline and Answer-Backtracking Diagrams:
<img src="https://tatlikazan-rv.github.io/assets/files/tMQA/pipeline.jpg">
<img src="https://tatlikazan-rv.github.io/assets/files/tMQA/answer_backtracking.png">


---




### Open-Loop Baseline for Reinforcement Learning Locomotion Tasks 

I have contributed to the publication [Open-Loop Baseline for Reinforcement Learning Locomotion Tasks](https://rlj.cs.umass.edu/2024/papers/RLJ_RLC_2024_18.pdf) by setting up and testing the simulation environment and hyperparameter optimization tools for the experiments.

---





### Obsidian Plugin - Live Text Translator from German/Turkish to English

This project was to solve a problem faced during note-taking for multilingual people. Specifically, when one word is remembered in one language but not the other and is written down that way, it causes problems with searching algorithms. To solve this, I have implemented a word based live text translator in the markdown-based note-taking app Obsidian.

---




### Trajectory Planning in Dynamic Environments

This project was to develop a reinforcement learning based algorithm to do trajectory planning for a mobile robot. A good real life application for this project would be a waiter robot for restaurants or cafes, where there are both stationary and dynamic obstacles on the way to the robot's goal destination.


<img src="https://tatlikazan-rv.github.io/assets/files/adlr/Gifs/plots/avoid_obs_sometimes/traj_check_2.gif" width=150 height=150> - <img src="https://tatlikazan-rv.github.io/assets/files/adlr/Gifs/plots/fails_to_avoid_if_headon_from_target_dir/traj_check_2.gif" width=150 height=150> - <img src="https://tatlikazan-rv.github.io/assets/files/adlr/Gifs/plots/waiting/traj_check_2.gif" width=150 height=150> 

Above you can see examples of avoiding obstacles, a failing example for trying to avoid head on collision directly coming from the goal position & succefully waiting for moving obstacles to pass. More information can be found in the presentation.

[Presentation](https://tatlikazan-rv.github.io/assets/files/adlr/ADLR_Github.pdf)

---





### Debate Clustering

This project was aimed at analyzing parliamentary debates by looking at the most common topics, understanding the participants' opinions on the topics and finally looking at how similar participants are regarding their opinions. For the sake of simplicity and relatability, the script of the series Game of Thrones was used as the hypothetical political setting.  

![Heatmap](https://tatlikazan-rv.github.io/assets/files/debate-clustering/overall_heatmap.png)

Above you can see an example heatmap style character similarity matrix. More information can be found in the poster.

[Poster](https://tatlikazan-rv.github.io/assets/files/debate-clustering/Argument-Clustering-in-Debate-Format-Game-of-Thrones.pdf)

---





### Echo Canyon: Lyric Generator incl. Rhyming Tool 

This project was aimed at developing a lyric generator that is for interactive songwriting. It's suitable for both beginners and professionals, where it has the following features (from paragraph to sentence level and then adjustments on word level):

- Starting from scratch or using parts of already written song lyrics
- Selecting a genre from blues, country, jazz, metal, pop, rock or basing the song on a specific artist (for copyright reasons the models for this aren't shared)
- Discarding lines entirely or replacing them temporarily with placeholders 
- Proposing alternative words to replace a specific word based on the line context
- Rhyming the last word of one line based on another line with 
    - pronunciation of the last word 
    - rhyme rating of the last word in a line on RhymeZone.com

Example Menu:

<img src="https://tatlikazan-rv.github.io/assets/files/echo-canyon/menu.png" width=500 height=300>

Above you can see an example for the basic menu from jupyter notebooks. More examples can be found in the presentation.

[Presentation](https://tatlikazan-rv.github.io/assets/files/echo-canyon/Echo-Canyon-Feature-Examples.pdf)

---





### Route Prediction in Roundabout with Neural Networks utilizing Prior Map Information

This project was my Bachelor Thesis in coop. with KIT-MRT and Scania Sverige AB. It focuses on the route prediction in roundabouts by trying to estimate the route of a vehicle utilizing lane information and the vehicles previous trajectory. 

<img src="https://tatlikazan-rv.github.io/assets/files/route-prediction/map.png" width=250 height=150>
<img src="https://tatlikazan-rv.github.io/assets/files/route-prediction/prediction.png" width=170 height=150>
