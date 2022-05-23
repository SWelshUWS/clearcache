# clearcache
Bash script to clear the memory cache.

Install in one of the directories in your $PATH environment variable.
To check for available directories:

	echo $PATH

Change user permissions with 

	chmod +x clearcache

usage: clearcache [type]

	1 - page cache
	2 - dentries and inodes"
	3 - pages, dentries and inodes"

example: clearcache 2
