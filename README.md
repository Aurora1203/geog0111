# Welcome to geog0111: Scientific Computing 
UCL Geography: Level 7 course, Scientific Computing

![](images/ucl_logo.png)

## Course information

### Course Convenor

[Prof P. Lewis](http://www.geog.ucl.ac.uk/~plewis)

N.B. 2018-19 Course Convenors: Dr Qingling Wu and Dr. Jose Gomez-Dans

### Course and Contributing Staff

[Prof Philip Lewis](http://www.geog.ucl.ac.uk/~plewis)  

[Dr. Jose Gomez-Dans](http://www.geog.ucl.ac.uk/about-the-department/people/research-staff/research-staff/jose-gomez-dans/)

[Dr Qingling Wu](http://www.geog.ucl.ac.uk/about-the-department/people/research-staff/research-staff/qingling-wu/)

[Mr Feng Yin](https://www.geog.ucl.ac.uk/people/research-staff/feng-yin)


### Purpose of this course

This course, geog0111 Scientific Computing, is a term 1 MSc module worth 15 credits (25% of the term 1 credits) that aims to:

* impart an understanding of scientific computing
* give students a grounding in the basic principles of algorithm development and program construction
* to introduce principles of computer-based image analysis and model development

It is open to students from a number of MSc courses run by the Department of Geography UCL, but the material should be of wider value to others wishing to make use of scientific computing. 

The module will cover:

* Computing in Python
* Computing for image analysis
* Computing for environmental modelling
* Data visualisation for scientific applications

### Learning Outcomes

At the end of the module, students should:

* have an understanding of the Python programmibng language and experience of its use
* have an understanding of algorithm development and be able to use widely used scientific computing software to manipulate datasets and accomplish analytical tasks
* have an understanding of the technical issues specific to image-based analysis, model implementation and scientific visualisation

### Timetable

The course takes place over 10 weeks in term 1, in the Geography Department Unix Computing Lab (PB110) in the [Pearson Building](http://www.ucl.ac.uk/estates/roombooking/building-location/?id=003), UCL. 

Classes take place from the second week of term to the final week of term, other than Reading week. See UCL [term dates](http://www.ucl.ac.uk/staff/term-dates) for further information.

The timetable is available on the UCL Academic Calendar

### Assessment

Assessment is through two pieces of coursework, submitted in both paper form and electronically via Moodle. 

See the [Moodle page](https://moodle-1819.ucl.ac.uk/course/view.php?id=2796) for more details.

### Useful links

[Course Moodle page](https://moodle-1819.ucl.ac.uk/course/view.php?id=2796)  

### Python version

These notes assume you are using python version 3.7

To verify that the current environment uses the new Python version, in your Terminal window or an Anaconda Prompt, run:

`python --version`

If this doesn't show 3.7.* then you may need to [update your environment and/or install a new version of python.](https://conda.io/docs/user-guide/tasks/manage-python.html)

### Obtaining and running course notes

The main coursenote repository is on [GitHub](https://github.com/profLewis/geog0111). You can acccess and download the notes from there.

To install these notes:

1. Make sure you are running the correct version of python (3.7) (see above)

2. make sure your conda and anaconda distributions are up to date

`conda update conda`

`conda update anaconda`

If either of these fail, try the following first:

`conda install conda`

3. Make sure you have git and pip installed

`conda install git pip`

You may also need:

`pip install --upgrade pip`

4. install the required dependencies

`pip install git+git://github.com/profLewis/geog0111@master`

### Course Notes

[Course notes](index.ipynb)  



### Problems

If you have trouble installing (or compiling) gdal, try:

`pip install --global-option=build_ext GDAL==`gdal-config --version``


OS X:  make sure xcode command line tools installed

`xcode-select --install`

and then check for updates in the usual way.
