# sqlite-demo

Small demonstration of sqlite usage in a data processing workflow.

The idea is to employ multi-threading (via a threadpool) and monitor the download status via a single-table sqlite database.

The sqlite-demo.ipynb notebook only demonstrates the concept. For a real application, you ned to think more carefully about the different states that can occur and how to deal with them.
