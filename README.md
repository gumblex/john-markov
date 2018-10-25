john-markov
===========
Stats files and Python implementation for the Markov mode of [JohnTheRipper](https://github.com/magnumripper/JohnTheRipper). See JtR's [MARKOV](https://github.com/magnumripper/JohnTheRipper/blob/bleeding-jumbo/doc/MARKOV) docs for more information.

* `john.stats` is the original stats file included in JohnTheRipper.
* `newdict3.stats` and `newdict4.stats` are the stats file of [these](https://mega.nz/#!Qwc1SQBI!rBmdEeZHICklyWNBq6YlaC6sFE_U5SWpM-VnRdy35R0) [two](https://mega.nz/#!txN3kJhb!2XituXIoBtSyRG-ue3B8vlJvhdUTiLrosse_utr2M7c) password dicts. The dicts contains all real passwords, and sorted according to [zxcvbn](https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/) scores.
* `username.stats` and `emailname.stats` are for generating usernames. The `username.stats` uses real usernames from various sources, and `emailname.stats` also includes the user part of emails.
* `markov.py` is the Python implementation as a library. You can use `python3 markov.py username.stats` to generate usernames for example.
