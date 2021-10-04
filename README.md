### How to use
1. *echofunc.vim* gets function information from tags file. Have to create tags file at first.
Using the following command to generate tags with language and signature fields:
#ctags -R --c++-kinds=+p --fields=+iaS --extra=+q .
2. Another feature of *echofunc.vim* is that to provide a balloon tip when cursor hovers a function name, macro name, etc. This feature is enabled when `+balloon_eval` is compiled in.
3. Enter "Insert Mode" and put cursor into parentheses in gvim, <Ctrl-h><Ctrl-j> to echo function info at message bar.
