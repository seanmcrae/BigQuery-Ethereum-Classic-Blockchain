# BigQuery-Ethereum-Classic-Blockchain
Complete live Ethereum Classic historical blockchain data (BigQuery)

Context

Ethereum Classic is an open-source, public, blockchain-based distributed computing platform featuring smart contract (scripting) functionality. It provides a decentralized Turing-complete virtual machine, the Ethereum Virtual Machine (EVM), which can execute scripts using an international network of public nodes. Ethereum Classic and Ethereum have a value token called "ether", which can be transferred between participants, stored in a cryptocurrency wallet and is used to compensate participant nodes for computations performed in the Ethereum Platform.

Ethereum Classic came into existence when some members of the Ethereum community rejected the DAO hard fork on the grounds of "immutability", the principle that the blockchain cannot be changed, and decided to keep using the unforked version of Ethereum. Till this day, Etherum Classic runs the original Ethereum chain.
Content

In this dataset, you will have access to Ethereum Classic (ETC) historical block data along with transactions and traces. You can access the data from BigQuery in your notebook with bigquery-public-data.crypto_ethereum_classic dataset.
Querying BigQuery tables

You can use the BigQuery Python client library to query tables in this dataset in Kernels. Note that methods available in Kernels are limited to querying data. Tables are at bigquery-public-data.crypto_ethereum_classic.[TABLENAME]. Fork this kernel to get started.
Acknowledgements

This dataset wouldn't be possible without the help of Allen Day, Evgeny Medvedev and Yaz Khoury. This dataset uses Blockchain ETL. Special thanks to ETC community member @donsyang for the banner image.
Inspiration

One of the main questions we wanted to answer was the Gini coefficient of ETC data. We also wanted to analyze the DAO Smart Contract before and after the DAO Hack and the resulting Hardfork. We also wanted to analyze the network during the famous 51% attack and see what sort of patterns we can spot about the attacker.
