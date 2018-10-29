# Testlet
Testlet is a Ruby on Rails based website, it targets for managing all kinds of tests, the name is inspired by Servlet, Portalet, Kubelet and most importantly Quizlet, besides coincidently I found out my first Github project name is “test”.

## Motivation
* Build a tool for managing various tests for effecient learning 
* Refresh my techie brain with latest techniques including Rails, Docker, K8S and etc
* Githubing and blogging

## Roadmap
### Milestone 1
Bootstrap a Rails 5.2 based website and package it into a docker-compose based app, which could be deployed to any docker env and usable for:
* Import choices (multiple/single) from CSV or running "http" cmd via shell/API end point
* Create a testlet based on all the choices
* Running test for one or multiple times
* Show and persist result, capable for exporting to CSV file/JSON output

## Notes
### Rails
* rails g model single_choice content:text, choice0:string, choice1:string, choice2:string choice3:string, answer:integer --force
