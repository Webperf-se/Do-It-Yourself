# Webperf – Do It Yourself
Detta är ett projekt med kodexempel som förhoppningsvis underlättar för dig när du vill hålla kolla på en webbplats.

[Webperf.se](https://webperf.se) är en webbplats som visar en topplista över svenska webbplatser, främst inom offentlig sektor, och baserar omdömet på ett antal tester. Testerna är öppna för vem som helst att använda om än ibland med vissa förkunskapskrav.

## För installation lokalt
Behövs för högre prestanda, köra mot intranät, känsliga data, etc.

Se till att du har:
* Python 3.6+
* Anaconda
* Jupyter (kan installeras när du startar Anaconda)

### Beroenden

Kör följande i din terminal:
* pip install beautifulsoup4
* pip install requests
* pip install pandas
* pip install matplotlib

### Extern dokumentation

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Requests](http://docs.python-requests.org/en/master/)
* [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)
* [matplotlib](https://matplotlib.org/)

## Intro till datakällorna

### Chrome UX report (Crux)
Kolla följande guide för att komma igång: 
* https://paulcalvano.com/index.php/2018/05/06/tutorial-using-bigquery-to-analyze-chrome-user-experience-report-data/
* https://webperf.se/articles/data-science-bigquery/