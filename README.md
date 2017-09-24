SCAP: a Simple Canvas LMS API Wrapper in Python
---
SCAP, an acronym for "Simple Canvas API wrapper in Python" is a package that attempts to 
simplify access to the [Canvas LMS API](https://canvas.instructure.com/doc/api/index.html). 
It is *not* completely implemented and honestly, I'm not planning to fully implement all end points.

There is **a great wrapper already available and actively being improved**, the
[Canvas API by University of Central Florida](https://github.com/ucfopen/canvasapi). 
You should definitely check it out.

Additionally there are other examples of incompletely implemented and/or abandoned 
wrappers in python such as:
* [CanvasLMS](https://github.com/lumenlearning/python3-canvaslms-api)
* [canvas-api-python](https://github.com/dkloz/canvas-api-python)
* [python-canvas-api](https://github.com/hawesie/python-canvas-api)
---
This project is unique for several reasons:
1. All calls return vanilla python dictionaries of the endpoint's json response. (Note: the 
UCF project often returns custom objects).
2. Impplements a sane OOP abstraction that should speak for itself. (Note: similar to both the UCF 
 and CanvasLMS projects).
3. Follows practices demonstrated in the
 [Building and Testing an API Wrapper in Python](https://semaphoreci.com/community/tutorials/building-and-testing-an-api-wrapper-in-python)
 tutorial. (Note: this is a learning opportunity for me).
 
If you'd like to contribute, all are welcome!
