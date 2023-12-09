# AIAA-Typst

This code repository contains a template and sample for authors interested in publishing conference papers for the American Institute of Aeronautics and Astronautics. It is based off of the template available from the AIAA webpage.
[AIAA Technical Presenter Resources Webpage](https://www.aiaa.org/events-learning/events/Technical-Presenter-Resources)

## Description

This repository contains multiple .typ files:
+ dropcap.typ  - This is a package that performs the dropcap it is authored by [EpicEricEE](https://github.com/EpicEricEE/typst-plugins)
+ main.typ     - This is the main file that is used to type your conference paper. Feel free to make any changes here.
+ template.typ - This is the supporting template file that provides the formatting for the template.

## Getting Started

Clone the repository using the clone button in the top right corner. You can download as a zip if you don't know how to clone and fork repos.

### Dependencies

* You will need to have [Typst](www.typst.app) installed.

### Installing

For mac users, I suggest opening a terminal and typing the command `brew install typst`. This will install Typst and add it to your path variables.
Once Typst is installed, navigate to the folder containing all the files from this repository in a terminal and type the command: `typst w main.typ`. This will compile the code and produce the pdf. As you make changes to the main.typ file, typst will continue to compile and update the pdf. Use command C to halt the terminal process when done. 

### Executing program

Once Typst is installed, navigate to the folder containing all the files from this repository in a terminal and type the command: 

```
typst w main.typ
```

This will compile the code and produce the pdf. As you make changes to the main.typ file, typst will continue to compile and update the pdf. Use command C to halt the terminal process when done. 


## Authors

Contributors names and contact info

Isaac Weintraub, Alexander Von Moll
The Dropcap project was coppied from EpicEricEE on Github.

## Version History

* 1.0 - The AIAA Template with Dropcap and sample bilibiography

## License

MIT License

Copyright (c) 2023 Isaac Weintraub

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
