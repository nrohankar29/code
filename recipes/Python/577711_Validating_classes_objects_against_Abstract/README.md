## Validating classes and objects against an Abstract Base Class

Originally published: 2011-05-20 22:38:59
Last updated: 2011-05-21 19:14:19
Author: Eric Snow

Abstract Bases Classes in Python provide great features for describing interfaces programmatically.  By default a subclass is validated against all its ABC parents at instantiation time (in object.__new__).  This recipe aims to provide for validation against an ABC of: