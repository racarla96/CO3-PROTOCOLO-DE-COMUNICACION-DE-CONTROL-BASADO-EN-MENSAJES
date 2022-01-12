# CO3 - PROTOCOLO DE COMUNICACION DE CONTROL BASADO EN MENSAJES

| Primitive Type 	|    C++   	| Python3 	|   Java  	| Simulink 	|
|:--------------:	|:--------:	|:-------:	|:-------:	|:--------:	|
|      bool      	|  uint8_t 	|   bool  	| boolean 	|  boolean 	|
|      int8      	|  int8_t  	|   int   	|   byte  	|   int8   	|
|      uint8     	|  uint8_t 	| int (*) 	|   (**)  	|   uint8  	|
|      int16     	|  int16_t 	|   int   	|  short  	|   int16  	|
|     uint16     	| uint16_t 	|   int   	|   (**)  	|  uint16  	|
|      int32     	|  int32_t 	|   int   	|   int   	|   int32  	|
|     uint32     	| uint32_t 	|   int   	|   (**)  	|  uint32  	|
|      int64     	|  int64_t 	|   int   	|   long  	|   int64  	|
|     uint64     	| uint64_t 	|   int   	|   (**)  	|  uint64  	|
|     float32    	|   float  	|  float  	|  float  	|  single  	|
|     float64    	|  double  	|  float  	|  double 	|  double  	|

(*) uint8 has special meaning in Python. uint8[] is treated as a Python bytes so that it is compatible with other byte-oriented APIs in Python.

(**) Java has no unsigned types to represent the uint8, uint16, uint32, and uint64 types.


##### Referencias:
- [ROS - MSG](http://wiki.ros.org/msg)

##### Tools used:
- [Tables Generator - Markdown](https://www.tablesgenerator.com/markdown_tables#)