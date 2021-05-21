```
eval$s=%w'b="BAhsK2Z/+AMAAAAAAP
APPw84AAAAAAAA8IDDAwcAAAAAAAA8c
PBwAAAAAAAAAA8HPA4AAAAAAADA4wDP
AQAADwAAAPAcwDMAAMADAAAAPAPwDwA
//AMeAAD/APwH8Bw84B8AwH8A/wE8Dg
8MDgDwH8DzAIDDgwMHADwP8HwA8PBwg
Pt/zwc8HPA/PBzg/t/DAQ8PDg8PBzgA
8PDAg8fBw8MBDgA8ePDAc/Dw4IABAA8
8PPA5vLxzOADAA58f/vwffPADAPjhDw
==";n=Marshal.load(b.unpack("m"
)[0]).to_s(2).reverse.scan(/.{1
,#{86}}/).join(""<<10).split(""
<<10);e="eval$s=%w"<<39<<($s*3)
;c=0;o="";n.each{|i|i.split("")
.each{|j|o+=j=="1"?e[c]:""<<32;
c+=j=="1"?1:0;};o=o<<10};o[-7,6
]=""<<39<<".join";puts(o)'.join
```

Vim
- 📻 https://github.com/kato-k/radiru.vim
  - listen Radiru-Radiru (Japanese internet radio provided by NHK)
- 😻 https://github.com/kato-k/nyancat.vim 
  - Run nyancat on your vim
- 🎨 https://github.com/kato-k/vim-colorscheme-settings
  - Switch Vim's colorscheme like VSCode
- 🏙 https://github.com/kato-k/vim-auto-color-switcher
  - Auto color switcher for darkmode of macOS
- 🚂 https://github.com/kato-k/vim-sl
  - SL command on Vim(WIP)
- 🔠 https://github.com/kato-k/Artify.vim9
  - artify.vim - written in vim9 script

Toy
- 🐠 https://kuragetool.github.io/
  - Webで動くツール

Articles
- 9️⃣ [Vim9script for Python Developers](https://zenn.dev/kato_k/articles/4585f83764f38b) 
- 🍵 [Vim Tips (Zenn)](https://zenn.dev/topics/vimtips)
- 📝 [Gist](https://gist.github.com/mine)

Translate (Contribute)
- 📔 Notally

[![](https://github-readme-stats.vercel.app/api?username=kato-k)](https://github.com/anuraghazra/github-readme-stats)
