---
title: Research Assistant Position in the Kihara Lab (lzerd.kiharalab.org)
updated: 2020-12-02 23:59
---

At the beginning of the Fall 2019 semester, I reached out to several professors hoping to get the opportunity to work in their labs. Dr. Kihara responded to me with interest, and late November, I had my first meeting with him. There I was introduced to the LZerD protein docking server.

The purpose of this server is to allow users to compare different protein docking configurations. For pairwise LZerD, two PDB files (proteins) are uploaded, along with some other constraints. After a brief period, the results can be viewed.

My first task for this server was to build out a registration and login functionality. Typically, users of the LZeRD server would submit multiple jobs, and having multiple jobs accessible on the server, rather than present in one's email, would be easier to navigate.

The server was built with Django and vanilla javascript, HTML, and CSS. Since it was my first time working with these technologies, there was a lot for me to learn.

Once I finished, I was tasked with building out the input form for MultiLZerD. As the name suggests, while pairwise LZerD docks 2 proteins, MultiLZerD docks at least 2 proteins.

After that was completed, and we received feedback on the server, I built out cosmetic changes for user accounts. I made use of bootstrap, added email verification, account deletion, username, and password changes in case a user is interested.

Currently I am working on expanding the input functionality to include IDPLZerD, a docking algorithm that uses a protein file with a protein sequence.

An article on the server has been published in a [Japanese journal](https://www.yodosha.co.jp/jikkenigaku/book/9784758125383/index.html).

You can check out the LZerD web server at [https://lzerd.kiharalab.org](https://lzerd.kiharalab.org)
