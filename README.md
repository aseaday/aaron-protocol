# aaron-protocol
A protocol for NFT/Digital Art has two features:
1. A Digital Art is more than a simple JPEG/MP3 and which should be played by an specific web app or software, we need to design a pattern which tells users how to display the digital art correctly.
2. The digital art on the blockchain should have markup language which support the information exchanging between the art works and chain information. 

## Introduction

A digital Art is an new type art works in the so-called web3 time, and most of nft/digital art stills use media format such as JPEG/MP3 to store and display which may violate the intention from its creator and some privacy rules. It is necessary to provide the information about which player to use and other fields like identifiers and vertification data. The aaron protocol defines an universal scheme of digital art and it is designed to sovle the problems above. 

For example, The JPEG format photo display software is default `preview` in the mac os, and it couldn't commnunicate with the web3 infrastructure because `preview` wasn't developed for showing a web3 digital art. A developer called Aaron wants to develop an player could shows markup <owner.name>, the markup <owner.name> is a information on the chain. One simple solution is to modify the suffix to an new symbol such as ".jpeg3", but it would break the compatibility for browersers and users who don't have player support `.jpeg3`. We should also provide the way to solve problem during the compatibility.

