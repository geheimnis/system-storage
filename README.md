Web Interface
=============

**Geheimnis** is a project consisting of several subprojects, that shall eventually made up an embedded system.
The system, including software and hardware, shall be able to connect to a PC via RJ45 or USB port, and is accessible to PC like a website providing HTTPS accessibility.
Either a user using his browser, or a software on PC using API to submit requests to this tiny website. Requests include, importing new _Contacts/Keys/Signatures_, requesting to encrypt/decrypt texts, etc. The software on this tiny hardware displays confirmation of such requests, then proceed and send out responds. Therefore, we say this project aimed at developing a device, that helps computer users authenticating, encrypting their communications. This device may also be a part of some kind of further systems, and helps automatically, e.g. for a system that controlling the entrance.

Introduction to this Subproject
-------------------------------

This sub project **system-storage**, is a directory, used to store all configuration files and all databases: e.g. codebooks, public-private keys, etc., related to the whole Geheimnis System.
The configurations for **web-interface** itself, are stored in its directory, not in this sub project.

Who is the author?
------------------
Not a good question. The author would like to be anonymous, at least on his true identity. To identify his true name and identity, here is the evidence.

    bfe28a734b1f4fbc0879db6f281ae9bb5d51d796d572a9f57ffb6c927340dd0f7d025228c9cb83e511978f70f36ce2eba12daf34a0befebf8f0bf1369857be5d

This is a hash in _Whirlpool_ algorithm, joining the name of his university which gave him a bachelor's degree, his student number, his true name, and even his personal identity number.
