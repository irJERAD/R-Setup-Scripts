# R-Setup-Scripts
Collection of Scripts to expedite and maintain consistency for setup of R and RStudio on a new machine

Approaches:
1. Single File to download all libraries and functions at once
2. Separate Folders and Files for different applications or use cases of the library / function / script
    - Individual Folders assume responsibility for entire setup
        - Even if multiple folders are used for same machine package manager will not download two copies of the same library so no need to worry about redundancy
    - Folder for sub groups like:
        1. Data Visualization
        2. Statistics / Machine Learning
        3. Presentations / Interactive Apps / Shiny

**TODO:**
- Once multiple folders are complete, change readme into table of contents / interactive navigation
- Create folder for All Inclusive setup which loads all libraries I use
- Folders:  
[ ] Data Visualization  
[ ] Statistics / Machine Learning / Data Science  
[ ] Presentations / Interactive Apps / Shiny / Dashboards  
[ ] Big Data  
