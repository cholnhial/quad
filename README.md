quad is a simple quick file utility used to transfer files 
over two computers via the internet.


## Requirements
32-bit intel Linux computer

## Building
To build quad you need to browse to the src directory.
type the following commands in your terminal:
`make`
(become root)
make install



## Usage
Downloading a file:
`quad -v -d -l 1337 -o ~/foo`

Uploading a file:
`quad -v -u -a 192.168.0.2 -i ./foo.txt`
