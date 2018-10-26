+++
title = "Ghosts for Lists: A Critical Module of Contiki   Verified in Frama-C"
date = 2018-01-01
authors = ["Allan Blanchard", "Nikolai Kosmatov", "Frédéric Loulergue"]
publication_types = ["1"]
abstract = "Internet of Things (IoT) applications are becoming   increasingly critical and require rigorous formal   verification.  In this paper we target Contiki, a   widely used open-source OS for IoT, and present a   verification case study of one of its most critical   modules: that of linked lists.  Its API and list   representation differ from the classical linked list   implementations, and are particularly challenging   for deductive verification.  The proposed   verification technique relies on a parallel view of   a list through a companion ghost array.  This   approach makes it possible to perform most proofs   automatically using the Frama-C/WP tool, only a   small number of auxiliary lemmas being proved   interactively in the Coq proof assistant.  We   present an elegant segment-based reasoning over the   companion array developed for the proof.  Finally,   we validate the proposed specification by proving a   few functions manipulating lists."
selected = "false"
publication = "*Nasa Formal Methods*"
doi = "10.1007/978-3-319-77935-5_3"
+++
