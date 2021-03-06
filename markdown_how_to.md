This is a quick guide to markdown syntax and tutorial styling for Mapping for the Urban Humanities summer 2019.


## General Style notes:
Tutorials should start off with learning objectives outlining skills to be covered, as well as a premise outlining the concept / question being investigated with the particular tutorial.

Tutorials should include brief conceptual descriptions of tools/processes being used but should assume that the theoretical foundations of these tools/processes have been covered in lectures/class discussion.

Its good to try to keep a through line that's connected to the premise with conversational notes about reason that we are about to embark on each methodological step. After the completion of that step, then, if applicable its often good to discuss any conclusions that can be drawn from it.

It has worked well to call out each major conceptual step with a section break and then each software step gets numbered within that section
For example:

#### Performing a table join
Description of why we are doing this and/or what this tool actually is.
1. do this
2. then do this
3. after that do this
Description of what happened.

A note on file structure for the github repository: save all tutorials in the root folder of the github repository **not** in the tutorials folder.

## Markdown syntax guide:

```
## Tutorial Title
```

```
#### Section break
```

To make a line break be sure to include two spaces at the end of your line.
Like that.  

lists:
```
1. text  
2. text  
3. text
```

1. text
2. text
3. text

bullets:
```
- first
- second
- third
```

- first
- second
- third

make things **bold**  like this:
```
**bold**
```
make things *italics* like this:
```
*italics*
```

Formulas can be highlighted with backticks `1 + 2 = 3`:
```
`1 + 2 = 3`
```

Include hyperlinks like [this](https://data.cityofnewyork.us) with this syntax:
```
[this](https://data.cityofnewyork.us)
```

For images:
1. use this syntax to embed it where you want to in the document:
```
![description of image one]
```
2. At the bottom of the document make a running list formatted as follows:
```
[description of image one]: Images/2019/image_file_name.png
```
3. Then place the image in the Images/2019 folder of the gihub repository

Screenshots/images should follow this naming convention: tutorial_name_01.png

![test image csr logo]

#### Markdown resources:
- [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code)
- [syntax](https://www.markdownguide.org/basic-syntax/)

### Resources about learning git and github:
- [git handbook](https://guides.github.com/introduction/git-handbook/)
- [cloning a repository](https://help.github.com/en/articles/cloning-a-repository)


------

[test image csr logo]:Images/2019/image_file_name.png
