Part 1:  5/5

Part 2:  2/5

20.3 - It's hard for me to tell what you're doing here when you've got multiple things going on to define `families` inside your code.  In both cases, it looks like you're trying to loop over the `families` variable, but the input that you're given is the `names` variable.  Try instead to loop over `names`.  Also, please feel free to reach out for help on Slack when you get stuck. -2

20.4 - You've got the start of this correct, in that you want to do a loop on `patients`, but you need to think a little bit more about what each `name` is going to be as you're looping over `patients`.

The first time through that for-loop, `name` will be `['Boal', 'Medical examination/evaluation', 1.1]`.  Therefore, `name[0]` will be `'Boal'`, `name[1]` will be `'Medical examination/evaluation'`, and `name[2]` will be `1.1`.

You had the right idea with getting the standard length of stay from `avg_los` with `avg_los[patients]` but should have used the diagnosis information as the key instead, as in `avg_los[name[1]]`.

Good effort, but not quite there.  -1