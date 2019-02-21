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

## Errata
There is an error in Table 5 of the paper. In the "true +" column, the overall sum should be 573, not 820, and accordingly precision, recall, and f-score are 0.92, 0.85, and 0.88.

[The reason for this error is in the Excel evaluation sheet, the total number of "true +" (573) was stored as number of "true +" for the chatbot corpus. Added up with the result for the other corpora (77, 170) we end up with 820.]

## License
All three corpora are released under the CC BY-SA 3.0 license.

## Content

### Ask Ubuntu Corpus
162 questions and answers from https://askubuntu.com.

Five intents (MakeUpdate, SetupPrinter, ShutdownComputer, SoftwareRecommendation, None) and three entity types (Printer, Software, Version).

### Web Applications Corpus
89 questions and answers from https://webapps.stackexchange.com.

Eight intents (ChangePassword, DeleteAccount, DownloadVideo, ExportData, FilterSpam, FindAlternative, SyncAccounts, None) and three entity types (WebService, OS, Browser).

### Chatbot Corpus
206 questions from a Telegram chatbot for public transport in Munich.

Two intents (Departure Time, Find Connection) and five entity types (StationStart, StationDest, Criterion, Vehicle, Line).

## Evaluation Scripts
Python scripts for automated evaluation are provided [here](https://github.com/sebischair/NLU-Evaluation-Scripts).

## Contact Information
If you have any questions, please contact:

[Daniel Braun](https://wwwmatthes.in.tum.de/pages/41usp76zyc49/Daniel-Braun) (Technical University of Munich) daniel.braun@tum.de
