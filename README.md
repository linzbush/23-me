
# **Exploring my genetic code from 23 & me**

A repo comparing my 23 and me raw data to SNPedia database using python in Jupyter Notebook

## Why look at raw data? 
#### Doesn't 23 & me tell me the same thing?

23 and me tells me a lot, but it doesn't tell me everything. My goal was to explore my raw data myself to see what else I could find, while also learning Python.
In addition, I wanted to find research articles that discussed my genes.

## What I did

To explore my data, I cleaned it up and matched my genes to data on [SNPedia](https://www.snpedia.com). For reference, SNPedia is a database containing information on variations in DNA.
Then, I found research articles that discussed my genes.
My final product is a document showcasing the top research articles for each of my genes.

## How I did it

First, I requested to download my raw data from 23 and me. This was easy to do and it was a quick turn around.
Once I had my data, I imported it into my file and got to work.
I had to clean it up a bit first. I changed my 'X' and 'MT' chromosomes to '23' and '24' and removed my empty Y chromosome to make the data easier to work with.
Then, I downloaded data from [SNPedia](https://www.snpedia.com) and matched my genes to it.
Now, I could visualize what my genes meant. I created new df to sepearate out my good genes, bad genes, neutral genes, and 'interesting' genes (>4 magnitude).

If I wanted to, I could search these genes on SNPedia or pubmed and find research supporting them. However, I wanted to try to make python do that work for me. So, I coded a way to find the top ten (if ten exist) research articles for each of my genes. 

My final output was a file containing information about these genes and links to the articles.

## Additional Resource and Acknoweldgement

This code was inspired by and adapted from Know Thyself: Using Data Science to Explore Your Own Genome by lorarjohns
