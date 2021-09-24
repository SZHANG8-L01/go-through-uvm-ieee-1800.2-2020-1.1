# uvm_void
The **uvm_void** class is the base class for **all UVM classes**. It is an abstract
class with no data members or functions. It allows for generic containers of
objects to be created, similar to a void pointer in the C programming
language. User classes derived directly from uvm_void inherit none of the
UVM functionality, but such classes may be placed in uvm_void -typed
containers along with other UVM objects.
```
virtual class uvm_void;
endclass
```
uvm_void is in uvm_misc.svh
