# in out error
Points: 275

## Category
General Skills

## Question
>Can you utlize stdin, stdout, and stderr to get the flag from this [program](files/in-out-error)? You can also find it in /problems/in-out-error_2_c33e2a987fbd0f75e78481b14bfd15f4 on the shell server 

### Hint
>Maybe you can split the stdout and stderr output?

## Solution
Upon running the file in the web shell, we get Rick Roll'd which is mashed up together with the flag.

The flag is printed as _stderr_, while the lyrics are printed as _stdout_

Redirect all _stdout_ into _/dev/null_ to only show the flag.

```


```

### Fl
