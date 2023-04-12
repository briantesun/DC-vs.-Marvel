# DC-vs.-Marvel

Note: I completed this project as part of a university course, so I'm unable to post the code publicly. If you want to see the code directly, I believe I can show it to you privately.

Summary: Data science project where I confirmed gender biases and derived other insights from a dataset of over 22,000 comic book characters from DC and Marvel using data visualization and statistics. I also made the initial datasets analysis-ready through data engineering tasks that included standardizing numeric data types and changing the index of each dataset to the name of each character. I've included some highlights of the project below.

Using data engineering to discover that, on average, DC features more heros than Marvel:

![final](https://user-images.githubusercontent.com/129823285/231052399-9ca5821a-7270-4866-9bca-c27260b766ea.png)

For context, the initial datasets looked like this:

![dc_raw](https://user-images.githubusercontent.com/129823285/231052465-dca6d9d1-e1fc-4653-bded-2e48e21a8a26.png)

Using a visualization to highlight that a p-value of 0.0206 led to a rejection of a particular null hypothesis:
![visualization](https://user-images.githubusercontent.com/129823285/231049782-35e3abde-31a9-4a09-a7e6-1672199f2041.png)

The following distribution of 10,000 bootstrapped proportions helped show that Marvel doesn't in fact have a population of nonbinary characters proportional to the population of nonbinary characters in the United States:
![bootstrap](https://user-images.githubusercontent.com/129823285/231054389-a03ed367-b493-449b-a244-1b48c30f335f.png)
