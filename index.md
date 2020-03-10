## Welcome to Rohith Balusu's Website!

![](Rohith.png)

### A Little Bit About Myself

I am currently a senior majoring in Econometrics and Quantative Economics at the University of Illinois at Urbana Champaign. In my free time I enjoy spending time with my friends playing board games, watching movies, and going out to eat. Some of my passions and hobbies include learning to cook new dishes and volunteering in the local community. In regards to my future aspirations, I am interested in pursuing a career in business, particularly with something related to the healthcare industry. 

### Blog Post Date 3/1/2020
I currently have the privilege of attending HackIllinois and learning about new projects to get immersed in. My favorite parts were interacting with the mentors, attending some of the side events going on like the 'GIT GUD AT GIT' and 'INTRO TO JAVASCRIPT WORKSHOP' events, and of course all the free food. 

### Blog Post Date 3/6/2020

Recently in my STATS 385 class, we had to code for using an existing database already loaded in Rstudio to create a density estimate curve for the famous Old Faithful geyser located in Yellowstone National Park in regards to the length of its eruption times. Attached below is the code I used from the dataset, 'faithful' to display an output of this comparison. I have not visiting Yellowstone yet but I mostly definitely will someday as I enjoy going on camping and backtripping trips, so this was definitely an interesting piece of information to mull over.

```markdown

# Plot the histogram with the density estimate curve
My Code Snippet: 

     faithful

     hist(x = faithful$eruptions, main = "Histogram of Old Faithful Geyser Eruption Time", xlab = "Eruption Time (mins)",
          breaks = 20, border = "dodgerblue", probability = TRUE,
          ylim = c(0, 0.8), xlim = c(1,6))
     lines(density(faithful$eruptions), col="red", lwd=2)
     box()
     grid()

```
Output: 
![](Code%20output.png)

### Linkedin
[Connect With Me!](https://www.linkedin.com/in/rohith-balusu-4991a1173/) 

### Github
[See What I'm Coding These Days!](https://github.com/brohith123?tab=overview&from=2018-12-01&to=2018-12-31)

### My Resume!
![](Resume.png)

### Thank you for visiting my site!
