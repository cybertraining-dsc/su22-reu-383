This is a document that I (Jackson Miskill) am using for notes, so that I can 
have a place to put everything that I am researching, rather than having it
in my notebook. 

# Cloudmesh

Cloudmesh is a service that allows users to interface with their computer
locally but also with cloud services. There are numerous API's within the 
service that allow this to happen. An API is an Application Programming
Interface; think about the term interface and how this applies to this. 

APIs are basically programs that make it easier to piece things together so
that the higher level functions can be built. Definitely important to understand
how everything goes together, I think. 

When we install cloudmesh, it installs a series of Git repositories. Which 
are all of the code necessary to make the whole API work and can also
be developed locally. 

What is an [API](https://www.youtube.com/watch?v=uNZlk3F_N7E)?

## Example APIs in Cloudmesh

**Console** is an example API. It is an API that enhances the print messaging
that goes on. It can produce colored printed texts, error tracebacks, etc. 
Verbosity of an output can be controlled with the `Variables` API. 

Banner prints a banner around the text you supply. 

VERBOSE is a method that allows you to print a dictionary. 

`dotdict` allows the user use a `.` to access values within a dictionary. 


**IMPORTANT** The `Shell` class was implemented in cloudmesh to allows easier
access to the command line (python has a built in way to do background tasks, but
it is not quite enough). Shell includes many functions that are decently typical
of a user utilizing the command line. 

`StopWatch` is important for timing events. 



