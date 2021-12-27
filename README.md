No Docs
=======

No docs is the best way to make others confused and upset after you have written
pretty open source libraries or applications. Real programmers are passionate about
technology and don't care about writing documentation, which is so coooooooool!

Getting Started
---------------

- Start by writing an attractive library or application. Then open source it.

- Do not write any documentation, or be vague. Leave the users confused.

- Think about the confusion and anger of the users. Celebrate it.

Advanced
--------

However, there are some techniques that are more worth learning than not writing
documentation at all. They are widely used in popular projects.

- Never give a "Hello, world!" example (aka. minimal working example). So that
  the users cannot figure out whether the software is not installed correctly,
  or whether there is something wrong with their usage.
  
  - **Example.** If you are writing a "getting started" tutorial for a new
    programming language you create, do not tell the user what the extension name
    of the language is. Imagine a user with an empty text editor and no idea what
    to do, not even being able to create a file with the right extension. That's
    great, isn't it? Let them waste their time in the search engines.
    
- Show attractive example illustrations to users. Increase their desire for this
  library or application. But, be vague in the tutorial, making it difficult to
  install or get start.
  
  - **Example.** If your project can be compiled from source, tell users what
    commands they need to compile, but don't tell them the path to the output
    executable.

- Write extremely detailed documentation, but in ambiguous natural language.
  Do not provide too many examples in formal language (aka. example code), so
  when users get into trouble, they have to look up answers in a mass of vague
  descriptions. Even better, when they ask questions in the community, you can
  blame them for not reading the documentation carefully.

- Automatically generate documentation from comments and source code. Experts
  can get the information they need from such documents, but not the beginners.
  Because of the "curse of knowledge", the beginners are not able to learn from
  community.

- Describe only the usage (API) of the library, but do not explain the purpose
  of it. Users will waste a lot of time before they find out that the library
  is not suitable.

Good luck!

License
-------

This project is licensed under the terms of the Unlicense, see
[LICENSE.txt](./LICENSE.txt) for details.
