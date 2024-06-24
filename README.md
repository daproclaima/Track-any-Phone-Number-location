
# Phone Number Location Tracker using Python 

One of my friends recently went missing... So I tried to commit to the research efforts with what I know doing best: 
coding.
Thankfully we found him back alive. 
This software will let you find the information of a phone number you provided. 
It accepts the international format (`+<country-code>`, but not `00<country-code>` ). 
Though, GPDR rules will not allow the third service this piece of code relies on to track the coordinates of a phone 
without its owner consent (only authorities are allowed to request these information to phone operator companies). You
will only find information about the operator company and its country.

This project is a fork of the repository of [Mohnaa Track-any-Phone-Number-location](https://github.com/Mohnaa/Track-any-Phone-Number-location/tree/Repositories).

## Installation

Install package with pip

```bash
  pip install phonenumbers
  pip install folium
  pip install geocoder
  pip install opencage
  pip install mechanize
  pip install bs4
```

Now need to collect Geocoder API Key from https://opencagedata.com/

Step1: Need to log in or sign up

![github1](https://user-images.githubusercontent.com/123636419/215339770-3cc5ba46-d502-42b9-9f15-856718cf22d1.PNG)

Step2: Need to click Geocoding API

![github2](https://user-images.githubusercontent.com/123636419/215339775-89aef127-2390-4f8d-8ad6-1129789eabab.PNG)

Step3: From API Keys collect API key

![github3](https://user-images.githubusercontent.com/123636419/215339773-0171d38c-b9ad-490a-95d8-47366321048a.PNG)

## Use
To run the program, make:
```bash
python main.py
```
To exit the program, type: `CTRL` + `D`
