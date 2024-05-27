# Toqen Subrgaph

<img src="https://raw.githubusercontent.com/toqenfactory/components/main/src/image.png" />

Discovery and indexing of all created ERC20 and ERC721 tokens using Toqen's React components.

#### GraphQL:

```
{
  tokenCreateds(first: 5) {
    id
    tokenAddress
    creator
    blockNumber
  }
}
```

#### Result:

```json
{
  "data": {
    "tokenCreateds": [
      {
        "id": "0x11d9f11dcaba9eb8399061d759362b72b5c5d800b4ae968995dea9534f5d3a3c00000000",
        "tokenAddress": "0x175c4faa937c5370f1b24be462095294c4ca647c",
        "creator": "0x65743fd07e4ce7a712da1ab18965e50c5b17317c",
        "blockNumber": "4106405"
      },
      {
        "id": "0x4319b88abae707715a7fe5c44beb9d5bffcf69b74611fb3a111d12b3b0e9086a00000000",
        "tokenAddress": "0xc1617d295ac97bcc42ddde592a330c8b4a570af5",
        "creator": "0x0faa656177455b1d1293d7724aeeb5f46a2f4f70",
        "blockNumber": "4388682"
      },
      {
        "id": "0x43e68ea5eb3f83c2ef2349fa60127c072bf62af4503a43cb17888b5f7fd17b2600000000",
        "tokenAddress": "0xdc49056e64c7e3791bee105bd23b6b79b081d61f",
        "creator": "0x65743fd07e4ce7a712da1ab18965e50c5b17317c",
        "blockNumber": "4107333"
      },
      {
        "id": "0x565321998e7caa150b17acef56f4472b21f6ece38483c08846a8285a2ddd5f2a00000000",
        "tokenAddress": "0xf057ab110f634dac525e507b768db29202d2526d",
        "creator": "0x0faa656177455b1d1293d7724aeeb5f46a2f4f70",
        "blockNumber": "4119380"
      },
      {
        "id": "0x5d13b7a435edd8f1fd00b16b98a7c6da23a1e3a98d6b54b53a44d8fe60352a7b02000000",
        "tokenAddress": "0x946607ed13004c87ccb143aaa36f8366ee140de4",
        "creator": "0x65743fd07e4ce7a712da1ab18965e50c5b17317c",
        "blockNumber": "4103019"
      }
    ]
  }
```
