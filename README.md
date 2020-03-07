Business/PayPal
============================

[![Build Status](https://travis-ci.org/szabgab/Business-PayPal.png)](https://travis-ci.org/szabgab/Business-PayPal)

This module attempts to make the automation of PayPal transactions as simple
as Credit Card transactions currently are.  This should allow PayPal to be
used in places it currently can not, such as online software sales, services
for immediate consumption, and in my particular case, conference registrations.
To this end, the module includes methods for creating PayPal buttons, of any
desired complexity, and methods for validating the Instant Payment Notification
messages that PayPal sends when a payment is made.

INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

DEPENDENCIES

List of dependencies can be found in the [Makefile.PL].

COPYRIGHT AND LICENCE

Copyright (c) 2002, mock <mock@obscurity.org>. all rights reserved.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

