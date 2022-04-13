# Classifying Video Games that Deserve Remastering & Re-relase 

![image](https://i.rtings.com/assets/pages/BZfoW14G/best-4k-gaming-tv-medium.jpg)

Authors: [Olamide Olayinka](https://www.linkedin.com/in/olamideholayinka/)

## Business Problem
Stakeholder: Bluepoint Games 
The Gaming industry is a huge indutry with it's marjet sizd currently valued at $86 Billion in just the alone. This consits of the several gaming platforms and consoles accesible today. Platforms/Consoles such as the Playstation( PS5 latest model), Xbox One(latest model) or the Nintendo Switch as well as PC games. All coming from their respective publishing companies such as Sony, Microsoft, Nintendo and so on. As the industry continues to grow and technology evloves, new systems tend to be developed, with better graphics, better frame rates and more ineratice capabilities for the users. While ew games tend to be developed, many users tend to desire playing the games they enjoyed growing up that may be from older systems or froma time when technology was limited. Where the graphics were limited and maybe not in 4k resoluton as many games are now. Thus introducing remastering and remaking these games.
 
 With a remaster, these game companies can rerelase old cult classic games with improvements to the hardware for uodated gaming. In addition games can also be remade. Taking these old games, and a process of shot-by-shot recreating it. So now the question becomes what games should be remastered. The **Stakeholder** : **Bluepoint Games**. Ive been tasked with buidling machine learing model and predicting which old games should be remastered or remade for this new age of gamers.

## Data and Preparation
The Date comes form the Video Games Data set vid Data.world https://data.world/sumitrock/video-games-sales. The Data set contains 16,719 entries as formatted in 16 columns. It contained the name of the Game along with the corrisponding Sales by region and gloably, as well as the other descriptive columns such as the Genre, Publisher, Rating, Developer and the Year of Release. Moreoevr, it also conatined User Score, Critic Score, User Count and Critic Count.With User score being the score a game user rated the game and the critic score being he score assigned by critics and publications.

Before moving on to the modeling, I dropped the ratings column due to it not being relevant to the business probelm at hand. Futhermore we I went on to create new columns for binning the user score and the global sales of games.  Specifying a range, I was able to create a these columns contain the value of "Low" for Sales and scores and 'High' for the higher scores and higer sales. These columns where later converted in binary columns 0 == "Low" and 1== "High'. This allowed for a smooth modeling process with Binary classification. 

### Methods


## Modeling



### Evaluation



![image]()





## Conclusions 



## Recommendations



## Next Steps
As for Next Steps, I would like to narow down a specifc criteria for how often after a game's initial release, should it be remastered. So based of the year of intial release, as well as the cycle of time it has been in circulation and it's user score and reception. In addition as I looked at Global Sales, I would like to go into Localized data and determined the games worthy of remastering based on it's sales and score per region. 

## For More Information
View the full analysis via the [Jupyter Notebook](https://github.com/olamide-h/Capstone/blob/main/EDA.ipynb).

