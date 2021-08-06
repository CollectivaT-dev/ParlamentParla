# ParlamentParla

Speech corpus for Catalan. The version 2.0 corpus can be downloaded in parts:

* [clean_train](http://laklak.eu/share/clean_train.tar.gz)
* [clean_test](http://laklak.eu/share/clean_test.tar.gz)
* [clean_dev](http://laklak.eu/share/clean_dev.tar.gz)
* [other_train](http://laklak.eu/share/other_train.tar.gz)
* [other_test](http://laklak.eu/share/other_test.tar.gz)
* [other_dev](http://laklak.eu/share/other_dev.tar.gz)

## Corpus information

This is the ParlamentParla speech corpus for Catalan. The audio segments were
extracted from recordings the Catalan Parliament Catalan Parliament 
([Parlament de Catalunya](https://www.parlament.cat/)) plenary sessions. We
aligned the transcriptions with the recordings and extracted the corpus. 
The content belongs to the Catalan Parliament and the data is 
released conforming their [terms
of use](https://www.parlament.cat/pcat/serveis-parlament/avis-legal/).

Preparation of this corpus was partly supported by the [Department of
Culture](http://cultura.gencat.cat/) of the Catalan autonomous government,
and the v2.0 was supported by the Barcelona Supercomputing Center, within
the framework of the project [AINA](http://aina.gencat.cat/) of the 
[Departament de Polítiques Digitals](https://politiquesdigitals.gencat.cat).

As of v2.0 the corpus is separated into 211 hours of clean and 400 hours of
other quality segments. The stat details are as follows:

| Subcorpus   | Gender   |  Duration (h) |
|-------------|----------|------------|
| other_test  | F        |   2.516    |
| other_dev   | F        |   2.701    |
| other_train | F        |   109.68   |
| other_test  | M        |   2.631    |
| other_dev   | M        |   2.513    |
| other_train | M        |  280.196   |
|*other total*|          |  400.239   |
| clean_test  | F        |   2.707    |
| clean_dev   | F        |   2.576    |
| clean_train | F        |   77.905   |
| clean_test  | M        |   2.516    |
| clean_dev   | M        |   2.614    |
| clean_train | M        |  123.162   |
|*clean total*|          |   211.48   |
|*Total*      |          |  611.719   |

For more information go to <https://collectivat.cat/asr>

## Revision log

* _2.0:_ Major changes in the file structure; speaker ids with respective
genders added. The speakers of train, test and dev corpora do not overlap.
A major increase in size with a total time of 611 hours 43 minutes.
* _1.0:_ Much better quality due to improved segmentation, corpus separated
into clean and other.
* _0.2:_ First public release of approx. 320 hours.
