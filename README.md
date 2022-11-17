# Hades - Dark web datasets (anonymised)  
This is the anonymised dark web dataset used for my university dissertation.

- onions.json.tar.gz - 83,098 records  
- images.json.tar.gz - 239,003 records  
- email.json.tar.gz - 195,668 records  
- crypto.json.tar.gz - 108,138 records  
- keyword.json.tar.gz - 75,504 records

The following fields are available from the compressed fils.

|     Selector                   |     Field                    |     Hashed    |     Clear Text    |
|--------------------------------|------------------------------|---------------|-------------------|
|     Onion service addresses    |     Onion service address    |     X         |                   |
|                                |     Title                    |     X         |                   |
|                                |     Page Hash                |     N/A       |                   |
|                                |     Technologies             |               |     X             |
|                                |     Last Checked             |               |     X             |
|                                |                              |               |                   |
|     Cryptocurrency             |     Wallet address           |     X         |                   |
|                                |     Type                     |               |     X             |
|                                |     Appearances              |     X         |                   |
|                                |                              |               |                   |
|     Email addresses            |     Email address            |     X         |                   |
|                                |     Type                     |               |     X             |
|                                |     Appearances              |     X         |                   |
|                                |                              |               |                   |
|     Keywords                   |     Onion service address    |     X         |                   |
|                                |     URL                      |     X         |                   |
|                                |     Score                    |               |     X             |
|                                |     Keywords                 |               |     X             |
|                                |                              |               |                   |
|     Images                     |     Onion service address    |     X         |                   |
|                                |     Source URL               |     X         |                   |
|                                |     Filename                 |               |     X             |
|                                |     MD5 Hash                 |     N/A       |     N/A           |
|                                |     SHA-256 Hash             |     N/A       |     N/A           |

Each file has been compressed, SHA-1 hashes of the zipped files are available below.

[onions.json.tar.gz](./onions.json.tar.gz) - 43fac0b0b14675ade34b70d15eb0b75e7a4283f6  
[images.json.tar.gz](./images.json.tar.gz) - 2e192298721d04a94e24cead5b929ffc25188998   
[email.json.tar.gz](./email.json.tar.gz) - 444cfb46d8c1e40fdd83d2c7a5757e494b729b84    
[crypto.json.tar.gz](./crypto.json.tar.gz) - bc7394aeb4d69be76c29c5d3bcbc0ed2c92aeb3c    
[keyword.json.tar.gz](./keyword.json.tar.gz) - be70b59885f568b5969a23552353c3261c56ce9b  

The dictionary used within the disseartion project (keyword analysis) is available [HERE](./dictionary.json)



