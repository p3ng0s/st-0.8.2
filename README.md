# st-0.8.2

st fork for p3ng0s ^^

## Patches
 - [st-doubleclick-tabcomplete-0.9.diff](https://gist.github.com/p4p1/173d0853a03f1abcafcf29883a82862d)
 - [st-invert-0.8.2.diff](https://st.suckless.org/patches/invert/st-invert-0.8.2.diff)
 - [st-font2-0.8.5.diff](https://st.suckless.org/patches/font2/st-font2-0.8.5.diff)
 - [st-scrollback-0.8.4.diff](https://st.suckless.org/patches/scrollback/st-scrollback-0.8.4.diff)

## Screenshots
<p>
  <img src="/img/black.png", title="demo"/>
  <img src="/img/inverted.png", title="demo"/>
</p>

## Tmux shortcuts

| Shortcuts | Action |
| --------- | ------ |
| `Ctrl-A S` | Sync Panes |
| `Ctrl-A P` | Log output to file in `/tmp/tmux-*` |
| `Ctrl-A r` | Reload Config |

## Set the bash / tmux bar variables

```bash
set-target -i 127.0.0.1 #IP
set-target -d google.com #DNS
set-target -u Administrator #USERNAME
set-target -p MYPassword123# #PASSWORD
set-target -H hash:ntlm # HASH
set-target -t ticket.file # KRB5CCNAME
set-target -s $PWD/scope.txt # SCOPE
set-target -U http://$DNS/ # URL
```
