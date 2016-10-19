# ProcessFilesInto2DArray

This code was implemented using C# in Visual Studio with the .NET Framework.

This method will take as input any directory and read all text files found. 

The first dimension of the array will represent each text file found and the second dimension will correspond to each line inside that text file. 

The first dimension of the array size is allocated according to how many text files are found in the directory. For each text file, the second dimension of the array is allocated according to how many lines that text file contains. 

In this way, we can allocate only as much space in the array as required for each text file. The rationale is that some text files may be large and others may be small, so we want to preserve memory storage. Also, by ensuring that the array is full, we can avoid accessing indexes with null values.
