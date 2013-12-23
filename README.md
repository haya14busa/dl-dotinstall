- [Vim - Command Lineで使用しているツールまとめ vol.1 - Qiita](http://qiita.com/PSP_T/items/10a9086de309cef5e185)
- [tmux - Command Line で使用しているツールまとめ vol.3 - Qiita](http://qiita.com/PSP_T/items/bd319bdaffb403d5e605)

```
sudo port install youtube-dl wget mplayer

mkdir -p ~/Movies/dt/ && cd ~/Movies/dt/
wget -r -I lessons http://dotinstall.com/lessons --user-agent=firefox
```

Update:
```
wget -r -I lessons http://dotinstall.com/lessons --user-agent=firefox
cd ~/Movies/dt/lessons/
ls > new_lesson.txt
よしなに編集
mv new_lesson ~/Movies/dt/lesson.txt
```
