# Data Engineer Challenge

## What is the purpose of this challenge?
With this challenge we would like to see a little bit more how you work and the way you make decisions, specifically, the challenge will help us see:

* your current technical knowledge
* your thought process
* the way you work and organize

The challenge will also help you get a glimpse of the real type of technical work we develop on our daily basis and the type of datasets we work with.

Please feel-free to surprise us, and showcase any skills that you think are important!.

Keep in mind that there is no right or wrong answer. If you feel like your process isn't perfect, don't worry. This is just
meant to be an exercise to help us gauge where you are in terms of your current capacity and be a talking-point during the interview.

## The challenge

### Overview

The challenge consists in creating a data pipeline that takes a raster dataset, summarizes it by administrative regions and stores the results in a medium that allows queries (a relational database or columnar oriented file). Specifically we want to summarize the total ecosystem carbon stock of the northern lakes region in the USA using the data of the National Forest Carbon Monitoring System.

The result must be the total carbon for each county of the states of Michigan, Wisconsin and Minnesota. To achieve it, we want you to create a simple Python pipeline that loads the rasters, computes the zonal stats and loads the values to a storage medium. The destination medium must allow a potential user to formulate queries easily and obtain the total carbon value for a specified county (for example, a posgresql database but feel free to use any data storage).

### The data:

- Use the raster from the National Forest Carbon Monitoring System. Specifically, we will focus on current state of the northern lake states region.
The data and metadata can be downloaded from: https://usfs-public.box.com/shared/static/v861gwms9fq68sitl0r3vs2v3moxeu9x.zip

- Use any administrative boundary source for USA counties you think is appropriate.

### Objectives

- Deliver a simple and reproducible python data pipeline.
- The pipeline must be easily reproducible end to end. This means that all the setup instructions or programs must be part of the deliverable.
- The results must be accurate and correct (watch out the units, there are some clues in the metadata documents.)
- Include instructions on how to query the results. The queries must work.

### The tools
Apart from Python, use any tools you are comfortable with.

## How should I deliver the results?
As a link to a repository on your preferred git platform (GitHub, GitLab, Codeberg...)

## How much time should I spend?
There is no time limit but we wouldn't want you to spend more than ~6 hours.

## What if I have questions?
Email us any questions and we will answer as soon as possible

## What will happen in the interview?
* In the upcoming interview we’ll focus on your coding challenge submission. We will **expect you to explain your code** to an audience that will include members of the Science team but also one or two people from other functional areas (Design, Front-End, Back-End, Project Manager,..). We will ask you any clarifying questions we might have.
* This will be an opportunity for you to provide some more context about the challenge, the assumptions you made, and add anything that you might want. The technical solution is not the only thing that we value, also your approach and explanations.
* Finally, we will also allocate some time for you to ask any questions about anything and everything you would like to know more about (ie. role, how we work at Vizzuality, our culture, benefits, etc.)
* The interview will last at most 120 minutes.
