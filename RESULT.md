### Result of task 4
 > *We do not know which thread writes to the output and this will confuse the system and might print the "wrong" value. This is because we use multiple cores and I'm not sure why and how. The example without gives no different results then with all of them, it might choose all when not specified. For only one core GOMAXPROCS(1), it gives the result 0.*
