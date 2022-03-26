# bash_oneliners


##### pull rows of a specific number, here four
`tail -n 4 somefile.txt > somefile_n.txt`


##### keep rows after a specific number, here four (see https://unix.stackexchange.com/questions/96226/delete-first-line-of-a-file)
`tail -n +4 somefile.txt > somefile_minus_n.txt`


##### create a sequence up to a certain number, iterating by 1
`seq 1 1000 > count.txt`
