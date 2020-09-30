# ObjVisSAP - Object Visibility Simple Access Protocol

The Object Visibility Simple Access Protocol (ObjVisSAP) is an IVOA Data
Access protocol which defines the standard for retrieving object
constraint-free visibility time intervals through a uniform interface within
the VO framework for given object coordinates to be observed by a given
Astronomical Observatory. The ObjVisSAP services can be registered in an
IVOA Registry of Resources using the VOResource, Extension standard, having
a unique ResourceIdentifier in the registry. The ObjVisSAP interface is
meant to be reasonably simple to be implemented by service providers. A
basic query will be done introducing a set of sky coordinates and a given
time period (optional). The service returns a list of constraint-free
visibility time intervals formatted as VOTable. Thus, an implementation of
the service may support additional search parameters (some of which may be
custom to that particular service) to more finely control the selection of
the visibility periods. The specification also describes how the search on
extra parameters has to be done.

# Status

Under development.

# Working on this Document

Remember to checkout the repository with its submodules.

    git clone --recurse-submodules https://github.com/ivoa-std/ObjVisSAP.git

Then: run "make" and hope you have all the necessary tools installed.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
<br />The IVOA Architecture document is licensed under the
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License</a>.
