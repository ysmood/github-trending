# Github Trending

This project is a tutorial for developers who want to learn basic knowledge about web scraping.
The goal is to scrape data from GitHub and rank the repositories based on the repositories you stared.

The knowledge required is just a basic understanding of coding.

To get the job done, we only need basic HTML and Golang knowledge.
This tutorial will assume you don't know anything about HTML or Golang.
If you already know them, you can skip some parts of the tutorial.

## Goal

Before we do a project, we'd better ask why we want to do it and how to measure the result, these the compass to prevent us from getting lost.

### To Answer the Why

Github has its trending of repositories, but they are mainly based on the stars of everyone, but you are not everyone.
So it would be nice to create a trending based ourselves to help us to find more high-quality projects that fit our own needs.

### How to Measure

This trending problem can be translated as a sorting problem. We sort the repositories by their star diff then find out the top ones.

- Do the top repositories still look good after we manually read their code?

- Do the higher-ranked generally look better than the lower-ranked after we manually read their code?

It's pretty intuitive to come up with the first question, but if we don't have the second question, it's easy to design something that only works well partially.
Usually the more good measurements the better final product will be. For this tutorial, we will focus on those two.

## Design the Weight Algorithm

We need a way to weight the repositories so that we can sort them. 

## The Approach

When doing web scraping we usually prefer to use the website's API direct to get the data we care,
but for beginners, it's usually more intuitive to scrape via the HTML pages. This tutorial will focus on HTML based scraping.
