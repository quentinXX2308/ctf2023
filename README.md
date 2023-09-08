# Supaero SDD CTF 2023

Question and data repository for the 2023 Capture the Flag.

## Questions

### Linux

1 | Where is the `curl` executable located? Some systems vary, if your answer is incorrect, try a common alternative.

2 | What is the linux command used for reading manuals?

3 | Where is the `less` executable located?

4 | What is the key for scrolling down by one half of screen size in `less`?

5 | What is the longer name of the `-K` flag to `curl`?

6 | What is the `cp` command flag allowing for copying directories? 

7 | What is the `ls` command flag used for human-readable output? 

8 | What is the `mv` command flag which will interactively prompt before overwriting files?

9 | What is the `cat` command flag which shows line numbers?

10 | If the variable `STRING` is set to `banana`, what does the command `echo ${STRING:4}$` return?

11 | If the variable `STRING` is set to `to be or not to be`, what does the command `echo ${STRING[@]/be/eat}` return?

12 | If the variable `a` is set to 3 and `b` is set to 4, what does the command `if [[ $a -le $b ]]; then echo $a; else echo $b; fi` return?

13 | If the variable `p` is set to `(3 1 4 1 5 9)`, what does the command `echo $((${p[0]} * ${p[2]}))` return?

14 | What is the `grep` command flag used to select *non-matching* lines?

15 | What is the longer name of the `-c` flag to `grep`?

16 | How many lines are in `file_a.txt`?

17 | What does the command `head -n 10 file_a.txt | wc -l` return?

18 | How many words in `file_a.txt` start with the letter "d"?

19 | How many words are in `file_a.txt` that contain only 4 letters?

20 | What is the last word in `file_b.txt`?

21 | How many words contain "ello" inside them in `file_b.txt`?

22 | What is the line number of the word "helicopter" in `file_b.txt`?

23 | What is the line number of the word "croissant" in `file_c.txt`?

24 | How many characters are in `file_c.txt`?

25 | How many words contain "croissant" inside them in `file_c.txt`?

26 | How many words end with the letter "t" in `file_c.txt`?

27 | How many words start with the letter "c" in `file_c.txt`?

28 | How many words have the letter "o" directly followed by either "u" or another "o" in `file_c.txt`?

29 | What word is at the same line in `file_c.txt` as the word "sheep" is in `file_a.txt`?

30 | What is the second word in `file_c.txt` which contains the letter `x`?

### Git

31 | How many directories are there in the root directory of the `machine-learning` repository?

32 | How many total files are there in the `machine-learning` repository and all subdirectories? Not counting directories or hidden files like the `.git` repository

33 | How many python or numpy files are in the `machine-learning` repository and subdirectories?

34 | What is the short version of the commit ID of the first commit of the `machine-learning` repository?

35 | What is the long version of the commit ID of the most recent commit of the `machine-learning` repository?

36 | What is the most recent commit message of the `machine-learning` repository?

37 | How many branches are in the `machine-learning` repository? Don't double count references to the same branch.

38 | What is the name of the branch which isn't `main` in the `machine-learning` repository?

39 | How many different unique user addresses have pushed commits to the `machine-learning` repository?

40 | What is the name of the LICENSE of the `machine-learning` repository? Hint: it is also the full first line of the LICENSE file

41 | What is the git remote "origin" url of the seaborn repository?

42 | What is the full version of the last commit ID in the 0.12 version branch of seaborn?

43 | How many commits are in the `master` branch of seaborn?

44 | How many tagged commits are there in the seaborn repository?

45 | How many "version" branches are there (ie, branches with a name starting in v)?

The following questions concern the `master` branch of seaborn.

46 | What is the last item of the seaborn repository's gitignore?

47 | What is the first line of the `setup.cfg` file in the seaborn repository?

48 | How many such key fields are in the `setup.cfg` file in the seaborn repository?

49 | How many files are in the seaborn repository? Not counting hidden files like the `.git` repository

50 | How many files directly contain the word "numpy" in the seaborn repository? Do not count hidden files like `.git/`

### SSH

51 | What is the name of the linux command used to generate SSH keys?

52 | What is the letter of the flag to specify the number of bits when generating an ssh key?

53 | What is the letter of the `ssh` flag that denotes the private key to use for authentification?

54 | What is the letter of the `ssh` flag to specify the user to log in as on the remote machine?

55 | What is the default port for `ssh`?

56 | What is the first default private key file used by `ssh`?

57 | What is the escape command to disconnect from an `ssh` pseudoterminal?

58 | What is the standard location of the per-user ssh configuation file in Linux?

59 | What is the keyword to specify the private key file in an ssh configuration file?

The following questions pertain to the remote server.

60 | How many files (excluding directories) are there in `~/`?

61 | What are the directories with binary executables accessible to the user (ie PATH)?

62 | How many binary executables are available to the user?

63 | What is the hostname of the server?

64 | What is the kernel name of the server?

65 | What is the release of the kernel of the server?

66 | What is the MAC address of the ethernet device of the server?

67 | What is the internal IP address of the server?

68 | What is the timezone of the server?

69 | What is the remote origin url of the git repository at `~/repo/`?

70 | What is the name of the file (without the path) that has been removed in the git repository?

71 | How many lines are in the file `~/repo/data/dogc.txt`?

72 | What is the last line of the file `~/repo/data/muni-cat.txt`?

73 | How many times does the word "biblioteca" appear in all files in `~/repo/data/`?

74 | How many `.txt` files are on the whole server?

75 | How many `.txt` files are in the home directory or its subdirectories?

### Linux

76 | What is the `apt` command used to install available updates?

77 | What is the letter of the `apt-get` command flag to perform a test run of the installation that does not actually change the system?

78 | What is the file which lists locations that `apt` fetches packages from?

79 | What is the name of the first column in `top` by default?

80 | What is the letter of the command in `top` to kill a process?

81 | What is the `tmux` command to list all running sessions?

82 | What is the `tmux` command to use an existing session?

83 | What is the letter of the tmux key binding to create a new window inside `tmux`?

84 | What is the letter of the tmux key binding to leave the current client without stopping it?

85 | If you run `tmux` on a remote server and then disconnect, will the `tmux` session end? "yes" or "no"

86 | What is the name for the tutorial command to learn `vim`?

87 | What is the name of the mode `vim` starts in by default?

88 | What is the command to quit vim, without saving changes?

89 | What is the letter used to navigate up in `vim`?

90 | What is the file used for a user's `vim` configuration?