# Lab Report 4: vim

# Part 1

## Changing the name of the start parameter and its uses to base

`` /start <enter> dw base <esc> i base <esc> n dw i base <esc> n dw i base :wq <enter> ``

*Using the /search command to find 'start'*

![vim_start](vim_start.png)

*Using dw to delete an entire word*

![dw](dw.png)

*Enter insert mode and type out 'base'*

![insert_base](insert_base.png)

*Escape to normal mode and use next for next instance of 'start'*

![n_find_start](n_find_start.png)

*Repeat 2 more times and then save and exit using :wq*

![vim_save_quit](vim_save_quit.png)

# Part 2

1. Editing in VSCode and then scp into remote

This took approximately 5 minutes for me to do, including making sure the scp command was correct. It took a while for me to make sure I had the corret scp command and I think it would have been faster to git clone or even ust locally copy the edits over. It also involved logging into the remote server, changing directory into the correct folder and then running to make sure it was correct. 

2. Editing in remote server using vim

This took 2 minutes because I just had to log into the remote server and locate the file then edit it directly instead of using the extra scp command and then logging in. The only difficulty I ran into while doing this was making sure I was editing the correct file because my remote server is not very well organized. 

*Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?*

If I had to work on a program I was running remotely I would prefer working entirely on the ssh remote server instead of logging on and off the server to make edits and then transfering it over. I think a lot of error can come up from forgetting to scp certain files over and a lot of error can be avoided when working in a single environment. 

*What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)*

If a project or task has to be run and tested locally I might use the scp method to do that and then upload the finalized code to the remote server. Otherwise, I think that most of the tests and the entire directory that has the scripts and the commands being on the server is the easier option when editing files. Also, because vim is built into the server there isn't any conflict between the programs that you are using. 












