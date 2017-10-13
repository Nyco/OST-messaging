# How to detect spam messages

The question was raised as currently there is a lot of spammers targeting XMPP users and very often server administrators are not aware about this issue. As this issue is quite new to XMPP protocol, there is small number of tools helping administrators to stop spammers.

During our discussion we found a few ideas on how we can detect spam:
* Messages usually have a long body
* On the server we have many messages with the same body
* Often spam is sent in language which is not spoken by recipient

We also mentioned that JIDs having a same email address are more likely to receive spam.

We discussed that there may be not easy way to fight spam with a XEP, but rather with good/best practices that are shared by servers operators/administrators.
