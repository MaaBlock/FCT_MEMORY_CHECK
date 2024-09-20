# FCT_MEMORY_CHEAK
a simple memory checking mechanism for dynamically allocated objects in C++.

it need c++11.

use FCT_NEW instead of new.

FCT_NEW(ClassName,param1,param2....);

FCT_NEW(ClassName,ObjectNum,param1,param2....);

use FCT_DELETE,FCT_DELETES instead of delete,delete[].

FCT_DELETE(object);

FCT_DELETE(objects);
