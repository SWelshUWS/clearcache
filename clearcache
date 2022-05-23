#!/bin/bash

if [[ "$1" == 1 ]]; then
    sudo sysctl vm.drop_caches=1 > /dev/null
    echo "page cache cleared."
elif [[ "$1" == 2 ]]; then
    sudo sysctl vm.drop_caches=2 > /dev/null
    echo "dentries and inodes cleared."
elif [[ "$1" == 3 ]]; then
    sudo sysctl vm.drop_caches=3 > /dev/null
    echo "page cache, dentries and inodes cleared."
else
    echo -e "usage: clearcache [type]\n"
    echo -e "\t1 - page cache"
    echo -e "\t2 - dentries and inodes"
    echo -e "\t3 - pages, dentries and inodes"
    echo -e "\nexample: clearcache 2"

fi
