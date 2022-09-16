# Four_Way_Associative_Cache-LRU-
This Four-way Associative Cache has a preset input (a list of addresses) to verify functionality but can be changed to handle any input.
The preset input takes the form of hexadecimal numbers which each represent a storage address.
This cache uses the Least Recently Used Algorithm to store data. 
Each address is parsed into chunks that respectively represent the c.tag, c.data, c.data.index, and c.tag.index.  
Each of these is displayed along with the Binary address, the stack history, the "Way" being utilized (There are four ways as implied by the name), 
and the status of Hit or Miss for each data entry. 
The preset input repeats itself several times to simulate the behavior of a cache(Without repetition there would be no hits). 
The hit ratio is printed at the end of the program and is varified to be accurate to the preset input data.
