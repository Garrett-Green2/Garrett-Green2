## Lab 01

- Name: Garrett Green
- Email: green.467@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [Garrett-Green2's GitHub Profile]([https://github.com/Garrett-Green2/Garrett-Green2))

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |    displays a list of the most used commands and their descriptions    |
| Get-Location | pwd    |  displays the current working directory    |
| Get-ChildItem | ls    |  displays the items in the current directory      |
| mkdir   | mkdir       |   creates a new directory     |
| Set-Location | cd     |   changes the current directory     |
| New-Item | touch      |    creates a new file    |
| Move-Item | mv        |    moves a file/directory to a different directory    |
| Copy-Item | cp        |   copies a file or directory     |
| Remove-Item | rm      |   deletes a file or directory     |
| notepad.exe | vim     |    opens a text editor in the terminal    |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: powershell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: C:\Users\Garrett
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir "Dir B"
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd "C:\Users\Garrett\Dir B"
6. Return to your user's home directory: cd ..
7. Create a file named `test.txt`: New-Item test.txt
8. Move the file named `test.txt` into `DirA`: Move-Item test.txt DirA
9. Contents of `test.txt`: cat test.txt
```
empty file
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp test.txt copy.txt
11. View the contents of `DirA`: dir
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp test.txt "C:\Users\Garrett\Dir B\fodder.txt"
13. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item "C:\Users\Garrett\Dir B"

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.



