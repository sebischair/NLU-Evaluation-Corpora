# README
This project is a collection of three corpora which can be used for evaluating chatbots or other conversational interfaces. Two of the corpora were extracted from [StackExchange](https://data.stackexchange.com/), one from a Telegram chatbot.

If you use the data and publish please let us know and cite our [SIGdial 2017 paper](http://www.sigdial.org/workshops/conference18/proceedings/pdf/SIGDIAL22.pdf):

```
@InProceedings{braun-EtAl:2017:SIGDIAL,
  author    = {Braun, Daniel  and  Hernandez-Mendez, Adrian  and  Matthes, Florian  and  Langen, Manfred},
  title     = {Evaluating Natural Language Understanding Services for Conversational Question Answering Systems},
  booktitle = {Proceedings of the 18th Annual SIGdial Meeting on Discourse and Dialogue},
  month     = {August},
  year      = {2017},
  address   = {Saarbrücken, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {174--185},
  url       = {http://www.aclweb.org/anthology/W17-3622}
}

```

## License
All three corpora are released under the CC BY-SA 3.0 license.

## Content

### Ask Ubuntu Corpus
190 questions and answers from https://askubuntu.com.

Five intents (MakeUpdate, SetupPrinter, ShutdownComputer, SoftwareRecommendation, None) and three entity types (Printer, Software, Version).

### Web Applications Corpus
100 questions and answers from https://webapps.stackexchange.com.

Eight intents (ChangePassword, DeleteAccount, DownloadVideo, ExportData, FilterSpam, FindAlternative, SyncAccounts, None) and three entity types (WebService, OS, Browser).

### Chatbot Corpus
206 questions from a Telegram chatbot for public transport in Munich.

Two intents (Departure Time, Find Connection) and five entity types (StationStart, StationDest, Criterion, Vehicle, Line).

## Contact Information
If you have any questions, please contact:

[Daniel Braun](https://wwwmatthes.in.tum.de/pages/41usp76zyc49/Daniel-Braun) (Technical University of Munich) daniel.braun@tum.de
