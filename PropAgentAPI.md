
PropAgent HTTP API
===========

## To create account

http://meshared.dynds.org:8567/CreateAccount?email=somnath@synptify.com&password=xxx

**Note** that password is optional and the proper HTTP type should be post.


## To populate catalog

You can send in email with an excel attached and subject line “configure <catalogId> <password>” to populate the catalog.
I am going to send you an example email in my next email.

**CatalogId** and **password** are mandatory for the time being. We can consider making either one or both optional.


## To access catalog

Once it is populated, you can pull it with http://meshare.dyndns.org:8567/GetCatalog?email=somnath@synptify.com&catalogId=xxx&password=yyy


