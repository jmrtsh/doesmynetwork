# doesmynet.work
(read: 'does my network work')
(the [long-awaited](https://github.com/kammt/doesmywifiwork/issues/5) sequel to [kammt/doesmywifiwork](https://github.com/kammt/doesmywifiwork))

If you're reading this, and you're not me writing this, then yes, it works. But now you can also check over at https://doesmynet.work.

Features:
- Dark Mode ([credit to aengelke; standing on the shoulders of giants etc.](https://github.com/kammt/doesmywifiwork/pull/3))
- localhost detection; which also means that if you host this locally, the site's observable behavior will be completely different, in order to ensure absolutely minimal testability (as if there were any).
- Optimized for binary size: at the time of writing, index.html is less than 512B, which, first of all, is one of the most neglected powers of two, and also happens to be less than the typical [MTU](https://en.wikipedia.org/wiki/Maximum_transmission_unit); so, disregarding all that pesky HTTPS protocol overhead, it possibly arrives on your device in only one IP packet!
- You're suppposed to have 3 or 5 bullet points, so I put 4 out of protest.

# NI (natural "intelligence") discloure

I hereby disclose that this project heavily (exclusively, in fact) used human intelligence in order to bring it to market as inefficiently as possible. All humans involved are free range, shade grown (houses provide a surprisingly high SPF, it turns out), and ~~grass~~*coffee*-fed. No animals were harmed in the making of this web page.


# Credit

All credit goes to the original idea over at [kammt/doesmywifiwork](https://github.com/kammt/doesmywifiwork). I only came up with a dumb other domain name.
