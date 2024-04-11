Welcome to my NIR Spectrometer GitHub Repository! 
There are three different types of files in this repository:
  1. NIR Spectrometer Casing and Module Design (Solidworks)
  2. Automated Data Compilation
  3. Classification Experiment Files
  4. Spectral Data Files

The first subsection of files or the "NIR Spectrometer Casing and Module Design (Solidworks)" is dedicated to all of the files associated wih the NIR spectrometer design. It includes the two part fragments that compose the NIR spectrometer casing, as well as four different modular cuvette attachments. These modular attachments are designed to be easily switched off depending on the sample composition and size. 

The second subsection is the "Automated Data Compilation" section and composes of a single file titled CompileCSV.py. This is a python folder that quickly compiles NIR spectral information provided in the Innospectra NIR Spectrometer format and deletes all information that is not absorbance. It also transposes the compiled data so that it can be readily plugged into the classification training models or for other purposes. 

The third section is called the "Classification Experiment Files". These files contain the actual experiments and the different classification models themselves. Inside this section are a series of python files that show visualizations of raw spectra, data-treatment methods, construction of the classification algorithm, testing of the classification algorithm with training sets, and testing of the classification algorithm with field samples collected in Malalwi. It also contains supporting csv files that were used in building the classification algorithm. 

The fourth section is called the "Spectral Data Files". This section contains the raw spectral data necessary to run this series of tests. 
