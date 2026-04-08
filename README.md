# Eigentiki-s-Quantum-Garden
my quantum playground, i think it's yours too, tap in gang!

I attended this lecture on Monday February 23rd, 2026 https://openlearninglibrary.mit.edu/courses/course-v1:MITx+8.370.1x+1T2018/courseware/Week1/lectures_u1_1/

I solved this problem set: 
https://drive.google.com/file/d/1NDSY6_v6QtGxmmmCtIqDHLCloG9E0v2T/view?usp=sharing

I solved this problem set 10:05am monday February 23rd, 2026:
https://drive.google.com/file/d/1EpX8rwJ5DCrVbgfMVSI5GNtPn_zPul25/view?usp=sharing

Matrix operation exercise at 10:23am Monday February 23rd, 2026:
https://drive.google.com/file/d/1z-eyra7gnlofqfIYrRWnh3OU3hbIgFAp/view?usp=sharing

I watched this lecture by the homie Shor:
https://openlearninglibrary.mit.edu/courses/course-v1:MITx+8.370.1x+1T2018/courseware/Week1/lectures_u1_1/

Physical and conceptual models of classical computation lecture at 10:45AM Monday February 23rd,2026:
https://openlearninglibrary.mit.edu/courses/course-v1:MITx+8.370.1x+1T2018/courseware/Week1/lectures_u1_2/?child=first


A brief introduction to computational complexity:
https://openlearninglibrary.mit.edu/courses/course-v1:MITx+8.370.1x+1T2018/courseware/Week1/lectures_u1_2/?child=first

Unitary and Hertian matrices problem set I solved at 9:19pm Monday February 23rd, 2026: 
https://drive.google.com/file/d/1QKT9IZurYmK8eU1IWK-MO-qbYPYcGRZ9/view?usp=sharing

My favourite matrix problems to solve EVER eigen vectors and finding eigen values:
https://drive.google.com/file/d/1cRTgWXdOdH_5zWntJ1FRyhBkiCdhYoc_/view?usp=sharing

Manipulating a Qubit with Single Qubit Gates at 10:22pm Monday February 23rd, 2026:
https://drive.google.com/file/d/1n5YqGE5GfbLLitysBov5reso7uB0xQG4/view?usp=sharing

Qubits and Superposition problem set solved at 10:38pm Monday February 23rd, 2026 :
https://drive.google.com/file/d/1GKJvcnoeWvvNkZb8C_-akbFK7h1_ZkHI/view?usp=sharing

I solved these Dirac notation problems for fun:
https://drive.google.com/file/d/115UdNgjfplj11LGWNCJ-l9Y2nleomDtl/view?usp=drive_link

Tuesday February 24th,2026:
I repped qubits on a BLoch's sphere for fun at the Chattime bubble tea store because I was bored:
https://drive.google.com/file/d/17nX1AFvfXybQujrjjGWWuHzdSYSi0SI7/view?usp=sharing


I factored out phases in this problem set:
https://drive.google.com/file/d/1n-hTOWaQQpIaZumdEuiZjhzZ816Goz7j/view?usp=sharing


Thursday February 26th 2026, I played around with Hadamard gate problems at the chattime bubble tea store for fun:
https://drive.google.com/file/d/1WljPwwyRMFIXo4mDyBrir4lM_oJ_uFhZ/view?usp=sharing


Thursday February 26th 2026, I played around with phase gates like S and T gates then noticed that an S gate is just the square root of a Z gate and a T gate is just the square root of an S gate in this problem set. Also I noticed the S ant T gates rotate the qubit around the Z axis:
https://drive.google.com/file/d/1NrACiU5IP7MOImGppQ2r_XChLqR_-xlv/view?usp=sharing


Friday February 27th 9:33AM I solved this probability problem with only solution 1 to start my day I will probably no pun intended pree solution 2 sometime in the future:
https://drive.google.com/file/d/1gQuqwxZfqTMBmXgQqGxLMP7c_7ItuPYP/view?usp=sharing

Friday March 6th 10:13AM I reviewed this probability problem with only solution 2 and the python simulation and it was interesting to see as more trials were added the probability kept approaching one-third the true probability:
https://drive.google.com/file/d/1gQuqwxZfqTMBmXgQqGxLMP7c_7ItuPYP/view

Tuesday April 7th 2026:
I wanted to build a search tool that could read Ontario government websites and answer questions, but I needed to do it without spending money on massive cloud servers. The biggest problem with AI is that it eats up way too much computer memory. Here is how I built it and solved the memory problem.

First, I wrote a quick Python script to scrape the text directly from the Service Ontario website. I grabbed the pages for renewing a driver's license and a health card so I had real, accurate data to work with.

Next, I used a free language model to turn all that text into long lists of numbers. In machine learning, this is called embedding. It basically translates English sentences into math. Sentences that mean similar things get assigned numbers that are close to each other. 

Then came the hard part. Storing millions of complex decimal numbers takes up way too much RAM. I tried to compress the memory by converting the decimals into small whole numbers. But since the original decimals were tiny, the computer just rounded everything to zero. I accidentally wiped the brain completely blank and the search tool broke.

To fix it, I used a trick called quantization. Before I squished the numbers into smaller data types, I multiplied all the decimals by 100. Doing this preserved the detail of the numbers while still letting me convert them into space-saving whole numbers. That one trick shrunk my memory footprint by four times without losing the actual information.

Finally, I wrote a search function. When I type in a question, the code turns my question into numbers and checks which government document has the most mathematically similar numbers. Because I compressed the memory so efficiently, the whole thing runs instantly on a free Google Colab graphics card.

Here is the Colab notebook:
https://colab.research.google.com/drive/1kxcksV67FCjJQ2fQrRNQIXwnoqRth3J9#scrollTo=v8ebftA8FQgz
