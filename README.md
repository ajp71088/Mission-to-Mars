# Mission-to-Mars

### Overview
BeautifulSoup and Splinter are used to scrape information and images from websites about Mars into a Mongo database. From there, Flask and Bootstrap 3 are used to create a mobile friendly website to display this data, with the ability for the user to click a button to have the data updated whenever they'd like.

#### Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
Images from the [Mars Hemispheres website](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) were gathered with the following code snippet:

![image](https://user-images.githubusercontent.com/107162310/185479949-f58e2644-9252-4af0-9259-9b7df2c88351.png)

The dictionary holding these links was then used in Deliverable 2.

#### Deliverable 2: Update the Web App with Mars's Hemisphere Images and Titles
The scraping python was updated to include Deliverable 1's hemisphere scraping and return the results.

![image](https://user-images.githubusercontent.com/107162310/185481056-765f218d-bcc1-4f67-9b0b-402e1e189fd0.png)

![image](https://user-images.githubusercontent.com/107162310/185480746-ef83dd73-3db7-4f8b-a70d-1324a5c7f7a0.png)

And then the index.html file was updated to display the returned images.

![image](https://user-images.githubusercontent.com/107162310/185481218-b8468040-4589-44f0-9dbb-69712ed8ae37.png)

#### Deliverable 3: Add Bootstrap 3 Components
The Scrape New Data button was edited to a new color:

![image](https://user-images.githubusercontent.com/107162310/185481408-03e9dd16-254d-4d9f-9600-9f20de715f31.png)

Some header text was emphasized (or italicized), and the title of the Mars Facts table was centered:

![image](https://user-images.githubusercontent.com/107162310/185481535-d2d3dcc5-63c7-42ec-a4aa-ef5d6f3ccb68.png)

### Results
The end result is a mobile friendly, easy to use website that will automatically grab the latest Mars news and images, alongside a table of facts and beautiful photos of the hemispheres, for fans of space to enjoy.
