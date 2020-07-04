# Accelerating Generalized Linear Models with MLWeaving: A One-Size-Fits-All System for Any-Precision Learning



## Abstract: 

Learning from the data stored in a database is an important function increasingly available in relational engines. Methods using lower precision input data are of special interest given their overall
higher efficiency. However, in databases, these methods have a hidden cost: the quantization of the real value into a smaller number is an expensive step. To address this issue, we present MLWeaving, a data structure and hardware acceleration technique intended to speed up learning of generalized linear models over low precision data. MLWeaving provides a compact in-memory representation that enables the retrieval of data at any level of precision. MLWeaving also provides a highly efficient implementation of stochastic gradient descent on FPGAs and enables the dynamic tuning of precision, instead of using a fixed precision level during learning. Experimental results show that MLWeaving converges up to 16X faster than low-precision implementations of first-order methods on CPUs.



## Bio:

Dr. __Zeke Wang__ is now a ZJU100 young professor at the Center at Collaborative Innovation Center of Artificial Intelligence & Department of Computer Science, Zhejiang University，China. He got its Ph.D. degree in Instrument Science & Technology at ZJU in 2011. 
