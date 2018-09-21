Advanced steps
==============

Expanding operators' behaviours
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Also you can expand language by defining new behaviour of operators "+","-","*","/".

To create new behaviour you can just create new function with name "plus", "minus", "multy", "division" relatively.::

    func plus(int a, double b):double{
        a|double + b >> return;
    }

And so on.
This may be useful to create behaviour of operators when you want to get sum of your Classes.

Also you have an access to builtin low-level operators::
    
    _+ # for adding integers
    _++ # for adding floats
    _- # for substracting integers
    ...

Pointers
^^^^^^^^

Pointer is "$".
Unpointer is "&"

If you came from c-type languages then you should be familiar with pointers.
There is a ability to get pointer to var.::

    0 >> age;
    $age >> y;
    &y >> out;
    # 0
    100 >> age;
    &y >> out;
    # 100
    
