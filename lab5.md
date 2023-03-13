# Lab Report 5
## Researching More Commands!
I decided to research more command-line options. Last time I looked into `find` options but this time I will look into `grep` options. I went about lab 3 by searching for helpful or interesting command line options and then testing and trying them out various of times. I think I really enjoyed this lab the most because I got to practice the material I learned in class and also expand on that. I got to practice more and refine my skills! The practice really helped me greatly which if why I choose to repeat this lab again by explore different command line options.

But back to the lab report, from what I've noticed, the difference between 'grep' and 'find' command line options is that 'grep' focuses more on a file's content and slightly on file name while 'find' is more focused on the file name and things relating to the file itself and not the content. For the following lab I will be using this text file called testing1.txt and testing2.txt. The first image is the content in testing1.txt and the second image is the content in testing2.txt.
(Image of testing1)

(Image of testing2)

I noticed that a lot of the command line options help with finding a specific word or phrase. One command line option was `grep -c` in which '-c' counts the amount of times the inputted word or phrase was used. In the following sample, I found the word 'file' three times amongst the two text files, and it also tells me how many times in each specific file.
(Image of grep -c)

One useful command line option I saw was `grep -h`. In this command line option, instead of listing the file name, it looks for the word then prints out the line where the word was found. In the sample I looked for 'file' again and as shown, it prints the lines in which file was found in.
(Image of grep -h)

There is another option that is extremely similar to `grep -h` and that is `grep -n`. '-n' is essentially the same as '-h' but '-n' includes the line number in which the line is at.
(Image of grep -n)

There is also an option that does the complete opposite of `grep -h` which is the option `grep -v`. '-v' returns the lines that does not include the inputted word or phrase.
(Image of grep -v)

Another interesting option was `grep -w` which is an option that looks for the full word. In this sample I've searched for 'con' and found the line that contained the word 'content' and when I added the option '-w' to the line, nothing is returned. So the '-w' option means that the word or phrase is strictly search for.
(Image of grep -w)

Finally I found one similarity between the two command line options, `grep -i` and `find -iname`. Both commands search for their files or things, but are case insensitive and so lower and upper case letters aren't taken into consideration. Here is an example of 'grep -i' being used and what occurs when I remove the option.
(Image)

I found more about grep options from [GeeksForGeeks](https://www.geeksforgeeks.org/grep-command-in-unixlinux/).
