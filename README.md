# average_location_file_based
file based version of the average location calculator

to use: 
1. make sure you meet the requirements
2. download and extract the files from the zip
3. make sure that you're connected to the internet
4. create a txt file containing your center location and addresses, following the format described below
5. place the txt file into the same directory as the .exe contained in this zip
6. run the .exe and follow the instructions


requirements:
- requires Python 3.11 or newer to be installed on your device (https://www.python.org/downloads/)

file format:
- lines can either be blank, contain ONLY a valid address, contain ONLY the word "center" or contain ONLY the word "location" followed by a colon
- valid addresses do not include suite or apt numbers

example file:
```
center:

9531 Bond Rd, Elk Grove, CA 95624

location:

9950 Elk Grove Florin Rd, Elk Grove, CA 95624
```
