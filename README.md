#Perclipse - The Eclipse Plugin for Perfidix

To make perfidix (http://www.perfidix.org) easy usable, an Eclipse Plugin is provided. This plugin is hosted in this repository.

##How to install Perclipse

* Install over Eclipse Marketplace, just search for "Perclipse" OR
* Get the lastest jar over Github and install by hand OR
* Get the latest release over the Update Site (http://disy.github.com/perclipse/)

##How to run Perclipse

* Annotate your methods to bench with "@Bench". Note that these methods have to have the following layout: "public (final) void method()" 
* Select "Run As" and "Perfidix Bench"

##Content

* README:					this readme file
* LICENSE:	 				license file
* feature:					The Eclipse Feature for the plugin
* plugin:					The Plugin itself
* updatesite:				The Update Site

##License

This work is released in the public domain under the BSD 3-clause license

##Further information

The documentation for Perfidix so far is accessible under http://perfidix.org (pointing to http://disy.github.com/perfidix/). Note that this Plugin generates overhead and has not the ability to empower perfidix like invoking it over dedicated void main-methods. It only there to offer fast execution of benchmarks

The framework including this plugin was presented at the Jazoon '07 as work in progress. The paper can be found over [here](http://nbn-resolving.de/urn:nbn:de:bsz:352-opus-84446).

Any questions, just contact sebastian.graf AT uni-konstanz.de

##Involved People

Perclipse is maintained by:

* Sebastian Graf (Perfidix Core & Project Lead)

and was implemented by:

* Lukas Lewandowski (Perclipse Plugin)

