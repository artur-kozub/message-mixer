# message-mixer
## This is basic console app builded with node.js without using any frameworks. Encoding and decoding. Can be runned without access to Internet.

Short **manual** for this one:

- node message-mixer.js ['caesar'|'symbol'|'reverse'] [amount]

    where "caesar" ([Caesar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)) cipher will shift characetrs of the input by alphabetic amount;
    symbol shifts specific characters to the similar digits;
    reverse doing the reverse string :)

- node super-encoder.js encode/decode will encode or decode your string depends on whether you will choose.

*Example:*

```
$ npm run caesar 7

Enter the message you would like to encrypt...
*>* my name is Artur


Here is your encrypted message:
*>* tf uhtl pz Hyaby
```

### All the commands:
```
    "caesar": "node message-mixer.js caesar",
    "symbol": "node message-mixer.js symbol",
    "reverse": "node message-mixer.js reverse",
    "encode": "node super-encoder.js encode",
    "decode": "node super-encoder.js decode",
```

#### Technologies:
   JavaScript, Node.js


> So, go nuts with this one (;
