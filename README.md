# Automatic-Music-Generation-System
## Introduction
Breakthroughs in artificial intelligence have created a variety of possibilities in the recognition, creation, and analysis of music through computational systems. To advance the expanding field, we sought to construct a network built from LSTMs that generates a sequence of pitches and durations which will construct a full song.The dataset used is a combination of O'Neill's Irish Music dataset and Cobb's Irish Music dataset and Nottingham Music dataset.

Long Short-Term Memory(LSTM) is an important technique used for music generation. LSTM is a type of RNN (Recurrent Neural Network) that solves some scenarios where RNN fails. LSTM solves the Long-Term dependency problem of RNN i.e. RNN networks store data of previous output in memory for a very short period of time. LSTM also solves the problem of Vanishing Gradient i.e. in order to get the best result, the model tries to minimize the loss after every time step by calculating loss with respect to some weights. After reaching a certain period, this weight becomes so less that it approximates to zero or vanishes and the model stops training.
## Problem Statement
The current technological advancements have transformed the way we not only produce but listen and work with music. And with the advent of deep learning it has now become possible to generate music without the need of working with instruments artists may not have had access to or the skills to use previously. This offers artists more creative freedom and the ability to explore different domains of music.
## Block Diagram
![image](https://github.com/niidhi10/Automatic-Music-Generation-System/assets/99705717/777024dd-662e-4c9d-b1dc-dbb9d0ffecfb)
## Algorithm
1. Import required libraries.
2. Read and Parse the Midi File.
3. Summarize the dataset.
4. Create input and output sequences for the model.
5. Divide the dataset into training and testing sets (80:20).
6. Build the model using LSTM architecture.
7. Train the Model.
8. Test the Model.
9. Save it into a MIDI file.
    
*Note: You may develop a web app or even a simple GUI to demonstrate this application.*
