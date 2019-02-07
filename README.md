# article-network
A Knime workfow for creating a similarity network from a collection of scholarly articles.

INSTALLATION
To run this workflow, you will need to install Knime first. Then, download and save the .knwf file in this repository and open it in Knime using the 'Import workfkow' command. All the necessary sample data is included in the workflow.

MORE INFO
This is a Knime workflow that I used to create a similarity network to visualise the articles that I downloaded during my PhD candidature. Some of the outputs that I created with the workflow can be seen on my blog at http://seenanotherway.com/a-thesis-relived-using-text-analytics-to-map-a-phd-journey/. Note that the network visualisations themselves need to be created with Gephi or some other software. This workflow merely creates the node and edge tables that can be loaded into Gephi.

The workflow includes some pre-parsed sample data, as I am probably not allowed to distribute the original PDFs, and they only make the download larger anyway. If you are game, you could load your own collection of PDFs into the workflow, but note that some parts of the workflow will expect the filenames to follow a specific format. A worthy addition to the workflow would be a sequence that matches up metadata from a citation manager with the PDF filenames, but I don't expect I will get around to doing this.

This is my first attempt and sharing a Knime workflow, and my first time using Github. I have no idea how this is going to work out, so go easy! If you get some value out of this offering, I'd love to hear from you. And if you use or recycle the workflow in another context, please credit me and link back to the Github page.

Good luck!
-Angus
