# Folder Structures
1. Codes = This folder contains all the python codes generated and used in this project. The name of the files are self-explanatory.
2. GIS raw database = This database contains all the raw GIS files. All the vector files and derived files are placed in Hackathon.gdb geodatabase.
3. Input feature tif = This folder contains all the generated input .tif files used in models input .csv database creation. These are factor maps.
4. Model = This folder has 5 sub folders, each for one mineral system. Within the subfolder it has generated final output images regarding model comparisons, statistical parametres and prospective maps both in .png and .tif format. The prospectivity map with proposed block boundary are also added. It has also have input .csv files for ML which are in 800m grid size. The project run on .csv file of 100m grid size where each file size is greater than 800mb, hence not uploaded due to size constrains.
5. Target tif = This folder contains target layers for each commodity having mineralisation and non-mineralisation points. This is used to test and train model.
