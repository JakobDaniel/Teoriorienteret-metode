# Teoriorienteret-metode
I download a dataset of alcohol consumption from 1880-2014 on www.ourworldindata.org/alcohol-consumption. Then I open my dataset in excel, and save it as ’tabulatorsepereret tekst’. Then I save it on my desktop with the name ‘Alko’. Then I open RStudio, and open a workspace. I press upload file, and on that workspace, I press ’import dataset’, and find my dataset ‘Alko’ in RStudio. 
To let RStudio know I’m going to use the data, I write ’attach(Alko)’ which is the name of my da-taset. 
Then I press ’mean’ V3 to find the mean of alcohol intake in litres for both sexes. The answer is 7.295238.
With a new dataset, I save it the same way as the previous set, as ’tabulatorsepereret tekst’ in excel, and save it on the desktop. This time, I will manually plot years and alcohol consumption in RStudio. 
I define my X and Y by typing: X <- c(1880,1920,1960,1970,1980,1990,2000,2014) and Y <- c(5.9,3.8,7.1,9.5,9.7,8.1,8.1,7.3). Then I write the command: plot(X,Y), And 
Then I want to name my axes where X stands for the year and Y stands for the alcohol consumption. I do that by typing the demand: plot(X, Y, xlab = "Year", ylab = "Alcohol Consumption"). 
To visualize my graph in a lineplot with marked points at the submitted years, I use the command: plot(X, Y, xlab = "Year", ylab = "Alcohol Consumption",type = "o") 

I want to make the ‘o’s in the graph entirely black so I use the command: plot(X, Y, xlab = "Year", ylab = "Alcohol Consumption",type = "o", pch = 20) 
 
Then I want to make the line more thick, and I use the command: plot(X, Y, xlab = "Year", ylab = "Alcohol Consumption",type = "o", pch = 20, lwd = 2) 
