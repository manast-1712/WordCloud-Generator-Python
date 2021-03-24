# PDF-Word-Cloud-Generator-using-Python
My Internship project on Word-Cloud Generator

Here, I have created a project which helps us create a Word Cloud from a given PDF. 
There's one limitation and that is of the pdf size, the uploaded pdf should not be very large ikn size.

# What is a Word Cloud?
Word Clouds are basically meant for visualizing the frequent words that appear in the uploaded document. They help in better understanding of structure of the uploaded document. The most amazing thing about word cloud is that only words which can make difference are considered i.e. in visulization stop words like conjuctions, articles are not considered. 
As there will be multiple words in a document, all such words will be displayed in word cloud. But, the space allocated to each word depends on frequency of that particular word in the document. More the frequency, more is the space allocated in word cloud to word.

For e.g. if a word "Python" is repeted most number of times in a document then it will be displayed with the largest size/font and, if a word "Code" ius repeated leastr number of times then its size in the image will be relatively smaller.

For examples of word clouds, refer: https://www.google.com/search?q=word+cloud&rlz=1C1CHBD_enIN837IN837&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjS5OO2yaLrAhUJyzgGHbBuDvAQ_AUoAXoECA0QAw&biw=1536&bih=743&dpr=1.25

# Below are the in build libraries and modules of Python that we have used in the project. 
Python

Flask

gunicorn

WTForms

Flask-WTF

matplotlib==3.3.0

numpy==1.19.1

Pillow==7.2.0

PyPDF2==1.26.0

wordcloud==1.7.0

# The site is hosted at : 
https://pdfwordcloudgenerator.herokuapp.com/

# For the Project Documents, Refer the following Drive Link:
https://drive.google.com/drive/folders/1D_ygt067Opl4KUw4XoVAC8lY8Cz6JxUo?usp=sharing


