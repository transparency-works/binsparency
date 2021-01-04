# binsparency
This repository is about moving binary transparency to distributed ledger technology (DLT).

Some projects focus on binary transparency as for example Mozilla https://wiki.mozilla.org/Security/Binary_Transparency. This is awesome!
All the components of a application are used to comprise a merkle tree. The head of the tree (hash) is then used within a certificate to proof it's authenticity. 
The certificates containing the hash of the merkel tree head is thereafter attestested and used to verify the integrity of the distributed application/files.
The above mentioned link (https://wiki.mozilla.org/Security/Binary_Transparency) lists in a very nice and compehensive way how to create new releases and how to verify a given release/file.

[@musalbas (Mustafa Al-Bassam)](https://github.com/musalbas) focused on moving binary transparency to the bitcoin blockchain. A comprehensive summary about his idea can be found at http://diyhpl.us/wiki/transcripts/building-on-bitcoin/2018/binary-transparency/. He proposes a transparent set of workflows for attestation and verification binaries/applications and anticipated a well defined set of actors and entities. It got named contour and is hosted at https://github.com/musalbas/contour.

Instead of moving the solution to the bitcoin blockchain (DLT). We propose moving it to [@BigchainDB](https://github.com/bigchaindb) a [@Tendermint](https://github.com/tendermint) based metadata DLT that is capable to store arbitrary JSON objects. Tendermint is a Proof-Of-Stake DLT and comes with no transaction costs. The network can be setup as a publicly available DLT or as a federated network.

The combination of the approaches by Mozilla (documentation of complex applications), Mustafa Al-Bassam (introduced processes, workflows, and core principles) , together with the simple but powerful design of BigchainDB to store arbitrary JSON objects combine the strong propositions of each proposal.

A first goal of this project is to sketch and draft the workflows for BigchainDB to attest and verify publishing organizations and their software/applications/products on the DLT. 

The goal of Binsparency is to work as a 2nd layer protocal on top of BigchainDB/Tendermint.
