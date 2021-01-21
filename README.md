# Front Matter
This is a collection of practice problems designed to assist students in Math 110. These problems have been obtained from a variety of openly available textbooks (see references).
Each question provides a link to the original source of the question. The hints, answers, and solutions are new.

# Acknowledgements
The creation of this resource was financially supported by the University of Victoria Open Educational Resources Grant.

# Colophon
Creative Commons BY-SA-NC

# PreText
This book uses [PreText](https://pretextbook.org/), an uncomplicated XML vocabulary for authors of research articles, textbooks, and monographs.

# To Contribute

All of the following instructions can be found on the [PreTeXt](https://pretextbook.org/doc/pnw/html/software.html) page.

## Download necessary tools

* Install Git by [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

* Download and install `xsltproc`, a command line tool for applying XSLT stylesheets to XML documents. [Download xsltproc](https://www.zlatkovic.com/libxml.en.html).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Instructions for downloading and installing `xsltproc` can also be found [here](http://mathbook.pugetsound.edu/documentation.html#getting-started-videos)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; It is recommended that you install the `xsltproc` in your default Git Bash directory in order to follow along with the commands.

* Sign-up for a github account. [https://github.com](https://github.com)

* Clone the mathbook repository to your root.  In your Git Bash shell:

&nbsp;&nbsp;&nbsp; `git clone https://github.com/rbeezer/mathbook.git`\
&nbsp;&nbsp;&nbsp; `cd mathbook`\
&nbsp;&nbsp;&nbsp; `git checkout dev`

&nbsp;&nbsp;&nbsp; Note: (`git pull` before each work session to make sure you're updated with the latest mathbook features)

## Compiling a PTX file

* Navigate to to the folder containing the PTX or XML file. 

&nbsp;&nbsp;&nbsp; Example: `cd Documents /c/Users/username/Documents/MATH110OER`

* Enter the following command to compile the main PTX or XML file.  

 &nbsp;&nbsp;&nbsp; `~/xsltproc/xsltproc --xinclude ~/mathbook/xsl/pretext-html.xsl index.ptx`

 ## Regularly contributing

 ### Pulling the latest changes from master
* To do
 ### Branching off of master
* To do
 ### Pushing up your changes and making a Pull Request
* To do
 
 ## Seeing the xrefs

 You won't be able to see the `xref`s when running locally because of the [Cross Origin Resource Sharing](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) issues.  Therefore, you can run a simple local host if you have python installed.  First check which version of python you have installed by running the command:
 
`python --version`

In the folder of your Math110OER repo, run the command (first is for python 2, second is for python 3)

 `python -m SimpleHTTPServer` or  `python3 -m http.server`

 Then go to 'http://localhost:8000/

You should now be able to see the references!  You can check this by going to any exercise and clicking on its resource link on the right.  