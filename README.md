# Private_AI_Differential_Privacy Udacity_Facebook_Challenge_Scholarship.

1.Creation of a virtual enviroment pysyft and installation of main libraries in conda:
conda create -n pysyft python=3
conda activate pysyft # some older version of conda require "source activate pysyft" instead.
conda install jupyter notebook
pip install syft
pip install numpy

2.Jupyter notebook 
Original database (db) contains 5000 entries (e.g. hypotetically each entry could represent a client)
Creation of parallel databases from the original database.
Each parallel database contains all the entries from db minus one entry (4999 entries each).
The aim is to create a list of databases (5000 parallel different databases, each one having 4999 entries)
