# ultragrep
Linux Based grep filesystem search for windows

### Usage ###

To run Ultragrep, startup a command line utility such as CMD or powershell. Navigate to the folder containing the program,
and execute the following command structure:

	ultragrep [-v] [folder] [regexstring] [extensions]
	
### Example ###

	ultragrep -v "C:/file/path/to/documents" [Hh]ello .txt.rtf
	
	
# Note	:	Do not include the square brackets [] for the above commands
	
	
### Parameters ###

[-v] 			=  	Verbose mode. Prints all matched words and the filepath to the file that contains the matched words, as well as the line
					number the words were found on. This parameter is optional.

[folder] 		= 	Any filepath. Filepaths that contain spaces MUST be surrounded by quotes "".
					This parameter is NOT optional and is required.

[regexstring]	=	Any regular string or valid regex expression.
					This parameter is NOT optional and is required.

[extensions]	=	Any file extensions seperated by a period. Ex: .txt.rtf.cpp.hpp.c.h.class 
					This parameter is optional.