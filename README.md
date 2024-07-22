# Stolen Bikes in Brussels: the process
 This repo contains the main official records and notebooks used for the data analysis of a project on stolen bikes in Brussels over the years. You can find the live html here: <a href="https://anaemepe.github.io/bikes-Brussels-project/">https://anaemepe.github.io/bikes-Brussels-project/</a>

 Additional records used on the data collection can be found on the <a href="https://www.police.be/statistiques/fr/criminalite">Belgian Police stats site</a>.

In this project, I searched to understand the trends of bike theft in Belgium, where I live. Around me and on the news I hear that more and more bikes are being robbed. 
I wanted to find out if official data could shed light on this.

I decided to focus only on Brussels as smaller rural areas of difficult access (eg Wallonia) or a strong biking culture (eg Flanders) could interfere in the analysis. 
The number of stolen bikes is increasing steadily every year. Compared to a decade ago, numbers have almost doubled. This is unlikely to be correlated with an increase of 
the population or a change in habits of the same magnitude. 

However, the most surprising finding is that bike theft consistently takes place in the second semester of the year, although according to 2023 data this could be about to change. 

On the data analysis process: I used a jupyter notebbok to analyse Belgium's public criminal records included in the repo and the link. They are a collection of PDF reports ranging from 2013 to 2023, with 2000 as a baseline. I first tried atttempted to use pandas to extract tables from the PDFs but it wasn't an efficient route. So after a reading analysis with the help of the documentation, I manually built a csv table with all the data points related to bike theft. 

I then used pandas to clean the data, analyse events and build subgroups of data points that then feed the charts, maps and illustrations.


## Skills, approaches, etc you used, or where you grew the most during the project
In this project, I intended to try out scrollama and ai2html. 

I also wanted to analyse public stats with a more informed methodology (eg. using documentation, analysis on pandas) as learnt at the Lede Program. 

Finally, I wanted to further explore creative ways of visualising that are at the service of communicating data. 

My approach was to build on and push the strong aspects of the project (visual scrollytelling) instead of aiming for the same weight in all elements. 

I have learnt **a lot** about ai2html and scrollama and have developed a raw methodology. Besides the technical aspect (I've spent quite some time revisiting tutorials and
solving a few technical bugs, but much less than I anticipated), one unexpected challenge was integrating this particular storytelling structure in my mental process. 

The design part also took some time as I was exploring ways of visualising while learning to use some figma and Illustrator tools. As usual, minor things (removing backgrounds!) 
took a disproportionate amount of time. 


## Things I tried to do or wanted to do
I would have liked to extract tables from PDFs on pandas in less time than extracting them on Google Sheets. 

I timidly attempted to add some animations but quickly understood it was going to take much more time than what I had available. 

While the minimalistic style is intentional, the visual elements, one of the aspects I wanted to explore in this assignment, can be further developed. The data analysis 
also leaves room for further exploration, that could be complemented with the views of authorities and people impacted by bike theft.

All in all, I regard this project as a prototype or a foundation to build upon.
