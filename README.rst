
derive(Rand)
============

Please read the `API documentation here`__

__ https://docs.rs/rand_derive/

|build_status|_ |crates|_

.. |build_status| image:: https://travis-ci.org/bluss/rand_derive.svg?branch=master
.. _build_status: https://travis-ci.org/bluss/rand_derive

.. |crates| image:: http://meritbadge.herokuapp.com/rand_derive
.. _crates: https://crates.io/crates/rand_derive

Recent Changes
--------------

- 0.2.0

  - Updated to use ``macro-attr`` which is the successor of the “``custom_derive``”
    crate. New syntax is to use ``macro_attr! { }`` around the struct or enum,
    and ``#[derive(Rand!)]`` with exclamation mark for the deriving attr.

- 0.1.0

License
-------

Dual-licensed.

Licensed under the Apache License, Version 2.0
http://www.apache.org/licenses/LICENSE-2.0 or the MIT license
http://opensource.org/licenses/MIT, at your
option. This file may not be copied, modified, or distributed
except according to those terms.


