**Early Popularity Analysis from Metadata & HITS Score**
This project connects and queries Azure-hosted SQL Server data to analyze early content performance using metadata and weekly popularity metrics.

We aim to join two key datasets:

Metadata Table: cp_lite.new_cp_metadata_estandar
Contains detailed movie/series metadata like title, genre, cast, country, synopsis, and release info.

HITS Table: dbo.hits_presence_2
Tracks weekly popularity scores and social media signals (Twitter, YouTube, IMDb, etc.).

By combining both, we can prepare a dataset to analyze what makes content popular in its first few weeks post-release.

🎯 Goals
Join content metadata with HITS scores.

Filter only early-week performance (week ≤ 3).

Enable downstream machine learning use cases like popularity prediction.

Support business teams with early insights into what drives viewership.

