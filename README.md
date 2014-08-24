XCast-
======

...	...	@@ -6,11 +6,11 @@
6	6	 //  Copyright (c) 2014 Black, Gavin S. All rights reserved.
7	7	 //
8	8	 
9		-#include <sys/sysctl.h>
10		-#include <mach/mach.h>
9	+#import <sys/sysctl.h>
10	+#import <mach/mach.h>
11	11	 
12	12	 #if TARGET_IPHONE_SIMULATOR
13	13	 bool is64bitSimulator();
14	14	 #endif
15		-BOOL is64bitHardware();
16	15	 
16	+BOOL is64bitHardware();
17	17	\ No newline at end of file
