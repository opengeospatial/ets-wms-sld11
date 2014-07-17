# OGC Web Map Service Style Layer Descriptor 1.1.0 Test-Suite

A Feature Portrayal Service (FPS) is a specialized "component" WMS
implementation that is able to portray feature data obtained from a remote
WFS. It supports user-defined layers and styles and in general has no pre-
defined layers; in this sense it is loosely coupled to any data sources. A
conforming FPS implementation must satisfy the requirements of **Conformance
Class C** in the SLD profile specification (OGC 05-078r4), plus all applicable
requirements in other relevant specifications

The OGC Web Map Service Style Layer Descriptor 1.1.0 Test-Suite provides the Executable Test Script (ETS) to test implementations against the following specification(s):

  * [OGC-05-078r4] [Styled Layer Descriptor Profile, Version 1.1](http://portal.opengeospatial.org/files/?artifact_id=22364)
  * [OGC-05-077r4] [Symbology Encoding Implementation Specification, Version 1.1](http://portal.opengeospatial.org/files/?artifact_id=22364)
  * [OGC-06-042] [WMS 1.3 Implementation Specification](http://portal.opengeospatial.org/files/?artifact_id=22364) (ISO 19128:2005)

Detailed information about this test suite is available [here]( http://htmlpreview.github.com/?https://github.com/opengeospatial/ets-wms-sld11/blob/master/src/main/web/index.html).

## License

[Apache 2.0 License](LICENSE.md)

## Building

This test is build using [Apache Maven](http://maven.apache.org/) To 
build the test suite run maven from the root directory.
   % mvn install
     
## To test an application:

For UNIX/OS Users
   - Clone this repository: **git clone https://github.com/opengeospatial/ets-wms-sld11.git**
   - Run **build.sh** at the root.

For Windows users and to get more information about running tests in TEAM Engine, check the instructions at the [CITE wiki](http://cite.opengeospatial.org/easytesting)

## Bugs

Issue tracker is available at [github](https://github.com/opengeospatial/ets-wms-sld11/issues).

## Mailing Lists

The [cite-forum](http://cite.opengeospatial.org/forum) is where software developers discuss issues and solutions related to OGC tests. 

## More Information

Visit the [CITE website](http://cite.opengeospatial.org/) to get more information about the CITE program and tools.

