# phrasegen
A simple and secure python script to generate memorable passphrases 

Uses EFF's [long wordlist](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt) with 55556 words. 
See the table on this Wikipedia [page](https://en.wikipedia.org/wiki/Password_strength) for entropy of generated passphrases.

## Simple installation & usage

```bash
$ git clone https://github.com/ephemer4l/phrasegen.git
$ cd phrasegen && cp phrasegen ~/.local/bin/
$ chmod ~/.local/bin/phrasegen
$ phrasegen
passlen: 7
Your password is:
nearby goon compactor cartoon prism livable excavator
```
