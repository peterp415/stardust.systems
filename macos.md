Add to your `.profile`:

    # For a dark iTerm background, using Dark Pastels
    # Also, set Background to #2c2c2c and Foreground to #dcdccc

    # Tell ls to use color
    export CLICOLOR=1
    # More readable ls colors on a dark background
    export LSCOLORS="exfxcxdxbxagadabagacad"

    # Tell grep to highlight matches
    export GREP_OPTIONS='--color=auto'

    # Colorful prompt
    # better on dark background
    export PS1='\[\033[00;35m\]\h\[\033[00;37m\]:\[\033[01;34m\]\W \[\033[00;36m\]\u\[\033[00;37m\]$ \[\033[00m\]'

    alias cp='cp -i'
    alias l.='ls -d .*'
    alias ll='ls -l'
    alias ls='ls -F'
    alias rm='rm -i'

    # virtualenv
    export WORKON_HOME=~/.virtualenvs
    source /usr/local/bin/virtualenvwrapper.sh
