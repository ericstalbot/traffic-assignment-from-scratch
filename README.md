# traffic-assignment-from-scratch
understand how popular travel modeling packages work by implementing their algorithms from scratch with python


- guiding principles
  - audience: practicing professionals who use travel modeling packages for their work
  - simplicity and clarity: the top priority when implementing the algorithms
    is that they are easy to understand. Performance considerations should only be a 
    side note or afterthought. Basic programming techniques should be chosen over
    sophisicated ones.
  - assignment: we only cover the assignment portion of travel modeling. we do not cover
    demand, distribution, mode choice, etc
  - visualization: algorithms should be illustrated with interesting visualizations, animations,
    interactions, etc.
  - Python and IPython: algorithms should be implemented in IPthon notebooks, with narrative.
  - references: references for algorithms should be given, but no reference is better than 
    a reference that is not suberbly helpful and well-written. Tutorial-type references 
    should have preference over original references.
  - popular packages: packages that use an algorithm (or some variation of it) should be 
    discussed in the notebook for that algorithm. Emphasis should be given to 
    algorithms used in popular packages used for professional work, rather than 
    experimental or academic approaches.
  - completeness: the note books should help users build an accurate mental model of the
    entire traffic assignment landscape.
  - from scratch: algorithms should be coded primarily with Python core, with the standard 
    library as needed. Third-party libraries should rarely, if ever, be used. This will 
    serve to dispell the "magic" surrounding commercial travel modeling packages. The
    one exception to this might be when programming visualizations, animations, etc. 

- topics to cover
  - approaches for modeling networks
  - shortest path algorithms
  - static and dynamic assignment
  - micro, meso, and macro assignment
