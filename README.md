# ***uisdata*** library
*uisdata* is a library for easy data access and manipulation of the datasets offered by the [**UNESCO Institute for Statistics** (UIS)](http://uis.unesco.org/).

## Library modules
*uisdata.bdds* is the first module developed to consume the dataset archives of the [**Bulk Data Download System (BDDS)**](https://apiportal.uis.unesco.org/bdds) repository. 

- Access any BDDS zip archive; download the archive from the repo to memory or access the archive on your local drive 
- Subset the datasets based on lists of countries, years and indicators
- Merge a dataset with its metadata (as columns or as a dictionary)
- Merge a dataset with its country and indicator labels
- Wrapper to do all the above with a single method
- Reshape tables from long to wide format (multiple options)
- Search utility to create lists of indicators and regions
- ... more to come ... 

## Source code and installation
The current beta version is hosted on PyPi at:  
https://pypi.org/project/uisdata/

## Python requirement
*uisdata* requires a python 64-bit version. 
It has not been tested extensively to find the minimal viable version, but it will work on: 
**python** >=3.6  (64-bit)

## Installation 
    pip install -i https://pypi.org/simple/ uisdata

## Modules Dependencies
*uisdata.bdds* has not been tested extensively to find the minimal viable versions for its dependencies.  
It requires the following libraries:  
**requests** - a standard for making HTTP requests in Python. It abstracts the complexities of making requests behind a simple API.    
**pandas** - an open-source Python Library providing high-performance data manipulation and analysis tool using its powerful data structures.    
**numpy** - NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices.

## License
MIT License

## Background
Work on *uisdata* started in 2021 for facilitating programmatic access to the UIS datasets. It is still under development, and I will be adding features in future iterations.

## Tutorials / use-case
[*.bdds* Use-case](https://datalore.jetbrains.com/notebook/FaD1hIZ0s0XKrlZcWTMYVW/UrrXOcYJWCstRNMNPvzzPF/) is provided through dataLore.  
Clone the notebook to your dataLore account (sign-up required). 
Note that the library will self-update to the latest version.

