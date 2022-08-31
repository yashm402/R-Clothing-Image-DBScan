# R-Clothing-Image-DBScan
Can we generate discernable groups of clothing images using the Density Based Scan algorithm? Under ideal conditions our primary method could be used as a label or categorization method for images. So, if the preparation of image files and DBScan method were acting accurately on the labeled on un-labeled image data and images could be classified. This would require perfectly masked scaled images, centered with very little noise.

***Image Dataset found here: https://www.kaggle.com/agrigorev/clothing-dataset-full?select=images.csv***

Q1.1: Where did you obtain your data set? Who collected it originally? If you know, what was the motivation for collecting the data? How many variables and observations are in the data set? Which variables are most important to explain to the audience?

Our dataset was obtained from Kaggle and it can be found at this web-page: https://www.kaggle.com/agrigorev/clothing-dataset-full. The dataset consists of 5,000 images of 20 types of clothing. The dataset is released under a public domain lisc. The lisc. means it can be used for any purpose. The originators used social media to gather the images and they ensured that contributors owned the images and agreed to the public lisc. The data was then labeled manually. Further details on the data-set can be found here: https://medium.com/data-science-insider/clothing-dataset-5b72cd7c3f1f.

Criteria 2: Appropriate exploratory data analysis performed

Q1.2: What kind of exploratory analyses/descriptives are appropriate for your data? What results of your exploratory/descriptive analytic work is most important to convey to the audience to facilitate their understanding of the data in support of the project topic?

The dataset included images and a csv to describe those images. First, we wanted to understand the counts of each type of label to ensure that we have enough examples of each type. This was done using a histogram. Next we dug into the to the image packages that we would need to use. Some of the functions that we needed was reading in the file, cropping, simplifying the image, down scaling, and turning to grayscale. From the augmented images we completed some initial distance calcs. It will also be important to explain why we may have done certain things, such and treating our images as a 1-D array.

Criteria 3: Research question presented

Q1.3: What question does your primary method (i.e., your topic) answer with regard to your data? 
Can we generate discernable groups of clothing images using the Density Based Scan algorithm?
Under ideal conditions our primary method could be used as a label or categorization method for images. So, if the preparation of image files and DBScan method were acting accurately on the labeled on un-labeled image data and images could be classified. This would require perfectly masked scaled images, centered with very little noise.

Criteria 4: Method for addressing research question explained

Q1.4: What is your analysis plan to use your data to answer your research question? What parts of this plan are most important to share with your audience?

We plan to compare the clusters obtained by the algorithm against the human labels of the categories of clothing.
We will do this using combination of histograms where we subset the clustered results and display the distribution of each category in the plot.

Criteria 5: Primary method explained in principle

Q1.5: If you had to explain your primary method to a classmate in writing but only had one page to do so, what information would you make sure to put on the page? Put differently, you won’t be able to fully explain any method during your presentation, but what aspects of your primary method must your audience know to understand your project?

I would ensure to include the details about the method the different parameters required to pass in the DBScan. I would also include the data preparation techniques, which include gathering the images and the subsequent steps required to prepare the images. Finally, I would include the some of my hypothesis about the flaws of the method.

Criteria 6: Application of primary method explained

Q1.6: Having heard your explanation of the primary method, would your audience understand your explanation of how you applied the method to your data? 

Yes, we took a logical approach. Which included taking understanding the raw data input, completed some sample calculations, and understood how the algorithm would work on the data.

Criteria 7: Data satisfaction of requirements of method demonstrated 

Q1.7: Did you articulate to your audience what properties the data must have in order to use your primary method (e.g., logistic regression requires a binary outcome...) and how your data meet these requirements (e.g., ...and the outcome of interest is binary)? 

For DBScan there was any very specific requirements for the data. It did not even need to be labeled, but to compare, contrast, and explain model performance we need labels.

Criteria 8: Primary new method applied and interpreted correctly

Q1.8: Is your primary method applied in a way that is appropriate for both the data and the research question? Is your interpretation of the results appropriate given your findings and the limitations of your method?

Yes, I feel that our primary method was applied in a reasonable way and our interpretation of the results are logical and valid.


Criteria 9: Supporting visualizations provided

Q1.9: Is there at least one visualization of your data or your analysis results? Do all visualizations support the audience’s understanding of the project? Can each visualization be at least partially interpreted without explanation from the speaker (e.g., Do axes have labels?)

Yes, we plan on having multiple visualizations, some of the initial data, some from source imagery, some from the imagery transform. We plan on having visual results of the clusters vs the original categories.
