Eppy
====
[![Build Status](https://travis-ci.org/jamiebull1/eppy.svg?branch=i70_continuous_integration)](https://travis-ci.org/jamiebull1/eppy)
[![Appveyor](https://ci.appveyor.com/api/projects/status/github/jamiebull1/eppy)](https://ci.appveyor.com/api/projects/status/github/jamiebull1/eppy)
[![codecov.io](https://codecov.io/github/jamiebull1/eppy/coverage.svg?branch=i70_continuous_integration)](https://codecov.io/github/jamiebull1/eppy)

Eppy is a scripting language for EnergyPlus idf files, and EnergyPlus output files. Eppy is written in the programming language Python. As a result it takes full advantage of the rich data structure and idioms that are available in Python. You can programmatically navigate, search, and modify EnergyPlus idf files using eppy. The power of using a scripting language allows you to do the following:

- Make a large number of changes in an idf file with a few lines of eppy code.
- Use conditions and filters when making changes to an idf file
- Make changes to multiple idf files.
- Read data from the output files of a EnergyPlus simulation run.
- Based on the results of a EnergyPlus simulation run, generate the input file for the next simulation run.

So what does this matter? 
Here are some of the things you can do with eppy:


- Change construction for all north facing walls.
- Change the glass type for all windows larger than 2 square meters.
- Change the number of people in all the interior zones.
- Change the lighting power in all south facing zones.
- Change the efficiency and fan power of all rooftop units.
- Find the energy use of all the models in a folder (or of models that were run after a certain date)

You can install from :
<https://pypi.python.org/pypi/eppy/>

The documentation is at:
<http://pythonhosted.org//eppy/>

to get a quick sense of how it feels to use eppy, take a look at
<http://pythonhosted.org//eppy/Main_Tutorial.html>

