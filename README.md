# opinion_seeker

an opinion system's data extractor

## design target

- there has two part of program
  - task controller for schedul the seek job
  
  - seek job, accept job from controller,
  
    and execute the configure script to extract document
  
- use rust to implement all logic

- use headless-chrome to extract data from web

- tag the website's part for extract document

  - every tag need some validation
  - when the tag extract failed, need warning and stop extract

- use mysql to save all the document

- use Elsticsearch to index the document for search
