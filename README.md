# sig-database
IDA FLIRT Signature Database


### Script
GitHub - push0ebp/ALLirt - [https://github.com/push0ebp/ALLirt](https://github.com/push0ebp/ALLirt)

### Sig List

* Ubuntu `libc6` `OpenSSL`
  * 4.10 (warty)
  * 5.04 (hoary)
  * 5.10 (breezy)
  * 6.06 (dapper)
  * 6.10 (edgy)
  * 7.04 (feisty)
  * 7.10 (gutsy)
  * 8.04 (hardy)
  * 8.10 (intrepid)
  * 9.04 (jaunty)
  * 9.10 (karmic)
  * 10.10 (maverick)
  * 11.04 (natty)
  * 11.10 (oneiric)
  * 12.04 (precise)
  * 12.10 (quantal)
  * 13.04 (raring)
  * 13.10 (saucy)
  * 14.04 (trusty)
  * 14.10 (utopic)
  * 15.04 (vivid)
  * 15.10 (wily)
  * 16.04 (xenial)
  * 16.10 (yakkety)
  * 17.04 (zesty)
  * 17.10 (artful)
  * 18.04 (bionic)

* Windows
    * VC12 - libcmt
    * OpenSSL
      * 0.9.8
      * 1.0.2

TODO : commit static libraries. please wait.

I encountered error in making signature on other architectures (mips, powerpc) with pelf (Unknown relocation type), so couldn't make pat file.

If you know solution for this problem, contact me and reflect it to these.

I used `launchpad.net`
please suggest me mirrors.


when I use `pelf` to make a sig (libc 2.27 latest), it caused error,
```
Fatal [/private/tmp/usr/lib/x86_64-linux-gnu/libc.a] (init-first.o): Unknown relocation type 42 (offset in section=0x3).
```
`-r` option not worked
you know solution?, please write issue. and commit this repository

