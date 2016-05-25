cdist-type__ungleich_staff_ssh_access(7)
=========================================
Give access to ungleich staff

ungleich GmbH <cdist--@--ungleich.ch>


DESCRIPTION
-----------
This cdist type ensures that the staff of ungleich
can access the target system.


EXAMPLES
--------

.. code-block:: sh

    # Grant access to root
    __ungleich_staff_ssh_access root

    # More explicitly
    __ungleich_staff_ssh_access anotheruser --state present

    # Remove access for ungleich staff
    __ungleich_staff_ssh_access root --state absent


SEE ALSO
--------
- `cdist-type(7) <cdist-type.html>`_


COPYING
-------
Copyright \(C) 2014 ungleich GmbH (www.ungleich.ch). 
Free use of this software is granted under the terms 
of the GNU General Public License version 3 (GPLv3).
