# Messenger-API
Generic Messenger REST API that receive a Message and make the dispatch for any Messengers (slack, email, whatsapp, any other api)

This is an open source project to help people who wants to use externalize the communication with the customers in a simple and scalable way.

You can use 1 or more dispatchers for your messages. Just implement the interface IDispatcher in the Service project to call any external API or MailBox and you will be good.
