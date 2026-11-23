# Navapp corrections

Verified corrections for [Navapp](https://github.com/TessDejaeghere/Navapp), the app for the correspondence of
the Belgian painter François-Joseph Navez (1787–1869), Navez Project, GhentCDH.

**The project historian is the authority here.** Navapp's automatic results (transcriptions, recognised names,
links to persons, chatbot answers) are suggestions; what is in this repository has been checked and corrected by
her. She publishes from her own copy of Navapp, from time to time (typically after finishing a batch of letters),
and every publication replaces the previous one. Nobody else publishes here.

| File | Contents |
|---|---|
| `manifest.json` | when the corrections were published, by whom, and how many |
| `notes.jsonl` | facts she corrected in the Navapp chatbot, one per line (the conversations themselves are not published) |
| `person_mentions.jsonl.gz` | the person mentions she checked in OpenRefine: which person is meant (with nodegoat ID), which mentions are not persons, and the corrected sender and recipient per letter |

Every copy of Navapp checks this repository, shows a notice when something new has been published, and loads it
with one click on the *Chatbot data* page. There, these corrections take precedence over the automatic results
and are read-only.

Errors in the source metadata (a wrong sender or date) are corrected in nodegoat, the project's reference
database.

Please do not open pull requests with corrections: send them to the project instead, so that they pass through
the historian.
