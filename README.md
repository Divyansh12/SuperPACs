# SuperPAC Project

superpac.biz, is a project examining the interactions of SuperPACs and political initiatives.

## Executive Summary

In today’s age of SuperPACs massive funding of politicians it is important for people to know who is influencing those that vote directly on our legislation. While the data for SuperPAC contributions is already available, our website seeks to combine this data with data about how the politicians they contribute to vote on legislation and present it using information-rich but intuitive visualizations, such that any concerned citizen can simply search for either a SuperPAC or a politician and be presented with visuals that easily allow them to “follow the money” from SuperPACs to members of Congress to voting on legislation.

## Project Description

The focus of our website is to create visualizations of how SuperPAC contributions to members of congress affect their voting on different pieces of legislation. A particular visualization, or set of visualizations, is presented when the user searches either for a specific member of Congress or for a specific SuperPAC. If the user searches for a SuperPAC, visualizations will focus on how that SuperPACs contributions to congressmen affect legislation. Conversely, if the user searches for a particular representative, the visuals will focus on what SuperPACs are contributing and how that is reflected in the representative’s voting on legislation. As the goal of the site is to inform, other relevant information, such as more information about a particular SuperPAC or politician, will be either given directly, or linked to, whenever possible.

# Setup Guide

## Docker

### database (MySQL)

### client (angular)

### server (django)
SuperPACs/
$ pip3 install django

Useful tutorial for understanding django.
https://www.youtube.com/playlist?list=PLQVvvaa0QuDeA05ZouE4OzDYLHY-XH-Nd

In restapi/rest/rest/settings.py, there is an encryption key that must be securely stored, out of production.
Stick it in an environment variable, and leave it out of the code.


## Virtual Environment for python 3.

Included in the gitignore is the file /superpac
it is meant to be the virtual environment file, there so you can work with the python 3 code even with python 2.7 installed.

SuperPACs/ $ virtualenv -p python3 superpac

A new folder will be created /superpac.

Now do $ python3 and python3 will start.

** may need to install python3 already? **

## Setting up Django.


# Software Design And Development Documentation.

## Style Guide

We have chosen style guides for Github, Javascript, Python, Object-Oriented Code, d3, and Angular.

https://docs.google.com/document/d/1Abvn7wZxvmLC8nWsMPAthzQ2oexTH3sDtC91zH7zmeI/edit?usp=sharing


## Deployment Diagram

https://drive.google.com/file/d/0B4fJ04kc6tHRQmFMUGpDQ1BFN0E/view?usp=sharing

## Domain Model

https://drive.google.com/file/d/0ByU5I4EWAyp5cjdSdFpBZ2xEa3c/view?usp=sharing

## Inception document

https://docs.google.com/document/d/1J4wr-IQZrq70X1NWiGK2sZdRkyR7uL44O6pK88FKAZk/edit?usp=sharing

## Elaboration document

https://docs.google.com/document/d/1J4wr-IQZrq70X1NWiGK2sZdRkyR7uL44O6pK88FKAZk/edit?usp=sharing
