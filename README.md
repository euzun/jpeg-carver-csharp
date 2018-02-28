# jpeg-carver-csharp
* This repo includes a C# toolbox for the orphaned jpeg fragment recovery method presented in following paper.
* This is a pure C# implemented code.
* WARNING: Check the dependency library to run the code!!!

## Dependencies
* Environment: Windows OS, .Net support
* Libraries: [MathNet.Numerics.dll](https://numerics.mathdotnet.com/) should be in the same folder with JpegRecovery.exe.


## Usage
* Example Usage: Type the following on command line or just double clickr "run.bat" file.
* JpegRecovery.exe "binary_file_name"
* Input: binary_file_name -> Binary data file e.g., raw_dragon
* Output: writes .jpg file in the same directory with input "binary_file_name" (e.g., raw_dragon.jpg)

## Folder Contains
* README.md: This readme file
* JpegRecovery.exe: Our C# Orphaned Jpeg Fragment Recovery tool.
* [MathNet.Numerics.dll]: Required library should be downloaded from https://numerics.mathdotnet.com/
* run.bat: Executer batch file to test the tool quickly. (Just double click)
* raw_dragon: A sample binary file that contains only encoded data of "full_dragon.jpg" file.
* orphaned_dragon.jpg: The recovered file you should get once run.bat executed.
* full_dragon.jpg: The reference sample full Jpeg file to compare with recovered orphaned file.

## Citation
* Please cite to following paper(s) if you use these tools for academic purpose;

* E. Uzun and H. T. Sencar, “[Carving orphaned jpeg file fragments](https://www.researchgate.net/publication/275044127_Carving_Orphaned_JPEG_File_Fragments)”, IEEETransactions on Information Forensics and Security, vol. 10, no. 8, pp.1549–1563, 2015.

