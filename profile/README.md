# .github

MAQ-Observations organization currently contains two repositories:
1) pre-processing
2) post-processing

Pre-processing contains all scripts to process raw data to readable format for the SQL database. It also contains the scripts that run operationally within WUR to update the database every 10 minutes. Most of the underlying data to run the scripts is not available, since this (raw) data is only accessible through WURnet. We do not intend to make this data public, that is what the SQL database is for. The pre-processing repository serves as version control for development, and inspiration for other to-be-planned near real-time databases.

Post-processing contains various scripts to retrieve, download and plot data through our API. Make sure to register at https://maq-observations.nl/api/ to be able to use these scripts. Here, we encourage collaboration from all interested parties.

Both repositories contain more detailed information and documentation.
