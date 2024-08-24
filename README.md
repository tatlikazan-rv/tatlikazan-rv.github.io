# NLP & ADAS

## Projects

### Developing Systems for Trustworthy Medical Question Answering (ongoing)

Developing a local-hosted (opt. cloud-hosted) Perplexity like GenAI (NLP-RAG) for medical research/consumer questions, based on scientific articles
- Focusing on privacy and interpretability, 
- handling 20 million research papers
- implemented for both MacOS & Ubuntu

```TODO:good example for chat UI and sources etc.```


### Trajectory Planning in Dynamic Environments

This project was to develop a reinforcement learning based algorithm to do trajectory planning for a mobile robot. A good real life application for this project would be a waiter robot for restaurants or cafes, where there are both stationary and dynamic obstacles on the way to the robot's goal destination.

<img src="https://tatlikazan-rv.github.io/assets/files/adlr/Gifs/plots/avoid_obs_sometimes/traj_check.gif" width=200 height=200> <img src="https://tatlikazan-rv.github.io/assets/files/adlr/Gifs/plots/fails_to_avoid_if_headon_from_target_dir/traj_check.gif" width=200 height=200> <img src="https://tatlikazan-rv.github.io/assets/files/adlr/Gifs/plots/waiting/traj_check.gif" width=200 height=200>

Above you can see examples of avoiding obstacles, trying to avoid head on collision directly coming from the goal position & waiting for moving obstacles to pass. More information can be found in the presentation.

[Presentation](https://tatlikazan-rv.github.io/assets/files/adlr/ADLR_Github.pdf)



### Debate Clustering

This project was aimed at analyzing parliamentary debates by looking at the most common topics, understanding the participants' opinions on the topics and finally looking at how similar participants are regarding their opinions. For the sake of simplicity and relatability, the script of the series Game of Thrones was used as the hypothetical political setting.  

![Heatmap](https://tatlikazan-rv.github.io/assets/files/debate-clustering/overall_heatmap.png)

Above you can see an example heatmap style character similarity matrix. More information can be found in the poster.

[Poster](https://tatlikazan-rv.github.io/assets/files/Argument%20Clustering%20in%20Debate%20Format%20Game%20of%20Thrones.pdf)



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