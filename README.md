# word-count-
Features a project that shows how to compute word count from a specific job description

The purpose of this project is to calculate the count of key words in a job description. It is part of a larger project where the system 
will be able to go into each webpage on a job search website such as LinkedIn or The Muse and then compute the word count of each important
word, so that a job seeker will be able to tailor their resume towards the job description by incorporating these key words. There are
websites that serve this exact purpose such as jobscan.io where a job seeker can copy and paste their resume as well as the job description 
for the job that they are applying for so that a word count can be returned.

I first picked a random job on LinkedIn and then I scraped the website so that I could isolate the main body of text. I then applied the 
the Natural Language Toolkit function to the body of text so that I could filter out all of the stop words when returning the word count
of the highest words. From their, I used the eye test to determine the word count of key words that make a huge difference on a Resume. 
