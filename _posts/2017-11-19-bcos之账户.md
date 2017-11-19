---
layout: post
title: bcos???
categories: [bcos, bcos]
description: ??bcos?????
keywords: bcos, account
---

# ??
bcos????????????????????????????????????????????????????????????? ??????????


# ????
bcos???????????????????????????????????? ????????????????????????? 20???????? /???????????????????JSON?????????????????????


<pre><code>
{
    "address" : "0065aaf34d2e71eafe6733d3470e501cd52d0caf",
    "crypto" : {
        "cipher" : "aes-128-ctr",
        "cipherparams" : {
            "iv" : "3a672facc8ac03699c60749c200003ca"
        },
        "ciphertext" : "f41427678daa07f1c47e8016a8fd45128318e8a0dda2d365c67667b0a1955f12",
        "kdf" : "scrypt",
        "kdfparams" : {
            "dklen" : 32,
            "n" : 262144,
            "p" : 1,
            "r" : 8,
            "salt" : "6eac965f623956d863cd6b6ce81e13bffeb30c0c466071c371eb2d8177be474b"
        },
        "mac" : "6199ff1df7ba43c984ec67242fcd2cfb0e97f72b83e6473a76fb6586a6748c44"
    },
    "id" : "7e1bb5a1-e93c-59d6-9ebd-cb1bc420c718",
    "version" : 3
}
</code></pre>

?? ??????????????????????????????????????????????????????????????????????????????????????????????????
# ????

??bcoseth??????????????boseeth??? ?????boseth account???
<pre><code>
root@xxxx:/# bcoseth account new
2017-11-19 23:26:03,562 TRACE [default] [dev::eth::ChainParams dev::eth::ChainParams::loadConfig(const string&, const h256&) const] [/home/administrator/workspace/c++/bcos/libethereum/ChainParams.cpp:124] genesisStateStr = {"0000000000000000000000000000000000000001":{"precompiled":{"linear":{"base":3000,"word":0},"name":"ecrecover"}},"0000000000000000000000000000000000000002":{"precompiled":{"linear":{"base":60,"word":12},"name":"sha256"}},"0000000000000000000000000000000000000003":{"precompiled":{"linear":{"base":600,"word":120},"name":"ripemd160"}},"0000000000000000000000000000000000000004":{"precompiled":{"linear":{"base":15,"word":3},"name":"identity"}},"004f9d39c8424e7f86004622cef21a0bbe140bfa":{"balance":"999999999999000000000000000000"},"00dcf3367eab3b34d6a598f453d1aee9146b50f3":{"balance":"999999999999000000000000000000"}}
2017-11-19 23:26:03,563 INFO [default] cp.dataDir=/mydata/nodedata-1/,cp.wallet=/mydata/nodedata-1//keys.info,cp.keystoreDir=/mydata/nodedata-1//keystore/,cp.logFileConf=/mydata/nodedata-1//log.conf,cp.storagePath=/mydata/nodedata-1//
2017-11-19 23:26:03,563 TRACE [default] [int main(int, char**)] [/home/administrator/workspace/c++/bcos/eth/main.cpp:468]  Main:: author: 0000000000000000000000000000000000000000
???keystore ?????/data/
keystoredir:/data/
2017-11-19 23:26:07,701 TRACE [default] [dev::h128 dev::SecretStore::readKey(const string&, bool)] [/home/administrator/workspace/c++/bcos/libdevcrypto/SecretStore.cpp:227] Reading/data/7e1bb5a1-e93c-59d6-9ebd-cb1bc420c718.json
2017-11-19 23:26:07,749 ERROR [default] Couldn't open wallet. Does it exist?

Enter a passphrase with which to secure this account:
Please confirm the passphrase by entering it again: 
Created key 095f1be4-561f-7896-02cb-c0ea7c93a634
  ICAP: XE451YY0HFNK7F8G3QAGG5XQFRI2AS6GDF
  Address: {0077f839c885255f1a557c82b8032fde15d23c63}
</code></pre>

?????????bcoseth account list
<pre><code>
root@u16042d:/mnt/hgfs/vmshare# bcoseth account list
2017-11-19 23:35:34,048 TRACE [default] [dev::eth::ChainParams dev::eth::ChainParams::loadConfig(const string&, const h256&) const] [/home/administrator/workspace/c++/bcos/libethereum/ChainParams.cpp:124] genesisStateStr = {"0000000000000000000000000000000000000001":{"precompiled":{"linear":{"base":3000,"word":0},"name":"ecrecover"}},"0000000000000000000000000000000000000002":{"precompiled":{"linear":{"base":60,"word":12},"name":"sha256"}},"0000000000000000000000000000000000000003":{"precompiled":{"linear":{"base":600,"word":120},"name":"ripemd160"}},"0000000000000000000000000000000000000004":{"precompiled":{"linear":{"base":15,"word":3},"name":"identity"}},"004f9d39c8424e7f86004622cef21a0bbe140bfa":{"balance":"999999999999000000000000000000"},"00dcf3367eab3b34d6a598f453d1aee9146b50f3":{"balance":"999999999999000000000000000000"}}
2017-11-19 23:35:34,048 INFO [default] cp.dataDir=/mydata/nodedata-1/,cp.wallet=/mydata/nodedata-1//keys.info,cp.keystoreDir=/mydata/nodedata-1//keystore/,cp.logFileConf=/mydata/nodedata-1//log.conf,cp.storagePath=/mydata/nodedata-1//
2017-11-19 23:35:34,048 TRACE [default] [int main(int, char**)] [/home/administrator/workspace/c++/bcos/eth/main.cpp:468]  Main:: author: 0000000000000000000000000000000000000000
???keystore ?????/data/
keystoredir:/data/
2017-11-19 23:35:41,878 TRACE [default] [dev::h128 dev::SecretStore::readKey(const string&, bool)] [/home/administrator/workspace/c++/bcos/libdevcrypto/SecretStore.cpp:227] Reading/data/095f1be4-561f-7896-02cb-c0ea7c93a634.json
2017-11-19 23:35:41,879 TRACE [default] [dev::h128 dev::SecretStore::readKey(const string&, bool)] [/home/administrator/workspace/c++/bcos/libdevcrypto/SecretStore.cpp:227] Reading/data/a25a7b43-0931-0683-cd7d-382971969e60.json
2017-11-19 23:35:41,879 TRACE [default] [dev::h128 dev::SecretStore::readKey(const string&, bool)] [/home/administrator/workspace/c++/bcos/libdevcrypto/SecretStore.cpp:227] Reading/data/7e1bb5a1-e93c-59d6-9ebd-cb1bc420c718.json
2017-11-19 23:35:41,879 ERROR [default] Couldn't open wallet. Does it exist?

Account #0: {0065aaf34d2e71eafe6733d3470e501cd52d0caf}
Account #1: {004629295e71a17e729bd28f40c7a5c55114d14f}
Account #2: {0077f839c885255f1a557c82b8032fde15d23c63}
</code></pre>


