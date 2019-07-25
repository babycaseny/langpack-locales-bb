locale-bb
=========

**locale-bb**-wa Babycasèny informeiçion sùpport dè sùpport à Linuks.  Sins 2009n dè 4m 2d, Babycasèny dè sùpport in Linuks wa aveilàbol. Sùpport-wa provaiden ŧru langpack-locales-2.3.18.16a (storen in tzsource dè fouldèr).  Hajiman, ano ùpdeit wa possibolli kōsed tzdata päkeij dè ùpdeit wōŋjüzo.  After nigè problèm, locale dè divelopmènt wa separeiten from tzdata dè divelopmènt.
Babyish locale fayls

**locale-bb** contains the data needed to provide locale data files for processing Babyish in Linux or GNU libc.  These information are provided by Babycasèny government.  Since 2nd April of 2009, Babyish support in Linux is available.  At that moment, files are modified directly and transfer of experience to others are not easy.  Later, a modified version of langpack-locales-2.3.18.16a was done to store tzdata information.  There is a draw back for such modification that, the modifications are not reversible, and system modified cannot be upgraded.  After this problem, locale development were separated from tzdata.  Now, the modification of tzdata are transferred to the glibc package.

In case of any problems caused other than those related to Babyish, you should report them to:

* http://sourceware.org/bugzilla/

Kontents-wa kopien tu folowen fouldèrs:
* charmaps usr/share/i18n/charmaps
* locales usr/share/i18n/locales
* locale.alias etc/


Si osou: 
* https://sourceware.org/glibc/wiki/Locales

Leitest ùpdeit:
* https://launchpad.net/ubuntu/+source/langpack-locales/2.13+git20120306-18

Locales definition files and formats:
* http://www.hungry.com/~pere/linux/glibc/
* http://man7.org/linux/man-pages/man5/locale.5.html
