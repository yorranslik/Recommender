# Recommender Werkenbij

This project serves as a trial project for Yorran. the goal was to create a very first recommender based on distance metric(s). After not working with Python for 8 months and not working in a data science environment for over a year and a half, it was fun to get some metres in the field again! This project builds upon some small NLP practises and uses the cosine similairity metric to calculate the distance between job vacancies at the WerkenBij website. The notebook then shows a graph to visualize the similairities and ends with a small function that enables you get the 'nearest x vacancies for your vacancy'. 

Unfortunately, this project won't go live as the current website does not support custom recommenders.

## Getting Started

As there is no support on Chromium, the author used BeautifulSoup to simple parse URLs. The URLS are acquired from Google Analytics (request access @ Yorran) and contain the URLs of all pages on the WerkenBij website. Simply uploading the list with URLs should suffice! 

### Prerequisites

No additional software is required, although the notebook uses several packages. 

```
See first codeblock in the notebook for examples
```


## Deployment

The project is not intended to go live. If ever doubting about going live with this: review the project thorougly! 

## Built With

* [NLTK](https://www.nltk.org/) - NLTK playground
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - URL Parsing
* [Spacy-NL](https://spacy.io/models/nl) - Werkwoordvervoegingen

## Contributing

Feel free to contribute, and above all upgrade.



## Acknowledgments

I would like to take my hat of for the entire ACE team, especially to

* Prashand - for standing by my side when I was in doubt!
* Chantal - for allowing me to play around with the recommender!
* My mum for raising me! 

