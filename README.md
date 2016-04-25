# cython_example_c-
small working example for cython c++
### Info

http://docs.cython.org/src/userguide/wrapping_CPlusPlus.html


https://studywolf.wordpress.com/2012/09/14/cython-journey-part-1/

Compilation
--------

    python3 setup.py build_ext --inplace

(run from inside module folder)



Usage
-----

    from rect import PyRectangle
( defined in the .pyx file )
    a_rectangle = PyRectange(2,2,1,1)
    #perform some operations in python
