CAWIP: a Canvas LMS API Wrapper in Python
=========
CAWIP, an acronym for "Canvas API Wrapper in Python" is a package that attempts to 
simplify access to the [Canvas LMS API](https://canvas.instructure.com/doc/api/index.html). 
It is *not* completely implemented and honestly, I'm not planning on finishing it. This is
a response to other examples of incompletely implemented, unmaintained and abandoned 
wrappers such as:
* [CanvasLMS](https://github.com/lumenlearning/python3-canvaslms-api)
* [canvas-api-python](https://github.com/dkloz/canvas-api-python)
* [python-canvas-api](https://github.com/hawesie/python-canvas-api)

All of the above work for their author's niche cases, which is great, but I find the
structure of their projects are an obstacle for me making improvements. This wrapper
will attempt to strictly follow simple practices demonstrated in the 
[Building and Testing an API Wrapper in Python](https://semaphoreci.com/community/tutorials/building-and-testing-an-api-wrapper-in-python)
Tutorial. It will also implement what I consider to be a sane OOP abstraction that should
speak for itself. I have no ambitions of completely covering all the API's endpoints, but hope the 
structure will be clear and its implemented features will at the least serve my personal 
needs. Unlike the above examples, features for exporting data in specific formats will be 
excluded from this project, until I change my mind about that. This should be extensible to
anyone's Canvas LMS API needs.
 
If you'd like to contribute, all are welcome!
