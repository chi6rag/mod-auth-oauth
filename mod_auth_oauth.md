# Introduction #

The mod\_auth\_oauth project consists of creating an Apache module that does all the OAuth processing in the context of an Apache module, in the request processing chain of Apache. This means that authorizing an OAuth transaction can now be done by the webserver, and this releases the processing from each and every (backend) service.

As such, it is an elegant way to support OAuth, requiring none to minimal changes to existing services to start supporting OAuth.


# Details #

  1. explanation of where mod\_auth\_oauth works in apache chain
  1. explanation of what mod\_auth\_oauth does **not** do
  1. explanation of link to backend token store
  1. explanation of debug possibilities
  1. explanation of OAuth in context
  1. explanation of HTTP response codes by