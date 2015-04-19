#1
In double average()¡Athere are arguments double *n1, double &n2
used the identifiers * as pointer, & as address ; which are passed by reference
In average()¡Athere are arguments int n1, float n2 ; which are passed by value

#2
 cout<<sizeof(a)<<" "<<sizeof(pa)<<endl;   //output:1 4
 cout<<sizeof(b)<<" "<<sizeof(pb)<<endl;   //output:4 4
 cout<<sizeof(c)<<" "<<sizeof(pc)<<endl;   //output:4 4
 cout<<sizeof(d)<<" "<<sizeof(pd)<<endl;   //output:8 4

a is a character = 1 byte(8 bit)¡Ab is an integer = 4 byte(32 bit)¡Ac is a float = 4 byte(32 bit)¡Ad is a double = 8 byte(64 bit). Therefore, the answers are 1, 4, 4, 8.
pointer pa, pb, pc, pd points to a, b, c, d individualy¡Astores a, b, c, d's address each¡Awhich are all integers¡Aand an integer = 4 byte. Therefore, the answers are all 4.

