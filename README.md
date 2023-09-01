Welcome to ChemoTyper
=====================

ChemoTyper application
----------------------

The ChemoTyper application is a tool that allows for searching and highlighting chemotypes (chemical substructures or subgraphs) in datasets of molecules. Typical applications are as follows.

*   Searching for structural alerts for toxicity in chemical structure files
*   Filtering of chemical structures according to chemotypes
*   Visualization and inspection of chemotypes
*   Grouping of chemicals according to chemotypes, and
*   Fingerprinting of chemical structure sets against chemotypes

The ChemoTyper application includes [​ToxPrint](https://toxprint.org). [​ToxPrint](https://toxprint.org) is a public set of chemotypes developed by Altamira LLC for the CERES poject of the US FDA Center for Food Safety and Applied Nutrition (CFSAN). The [​ToxPrint](https://toxprint.org) library contains three basic subsets.

*   Generic structural fragments
*   Ashby-Tennant genotoxic carcinogen rules [​(Ashby, J.; Tennant, R.W., 1988)](http://dx.doi.org/10.1016/0165-1218(88)90114-0)
*   Cancer TTC categories [​(Kroes, R. et. al. 2004)](http://dx.doi.org/10.1016/j.fct.2003.08.006).

Publications about ToxPrint chemotypes, CSRML language, and ChemoTyper application
----------------------------------------------------------------------------------

*   [​Yang C, Tarkhov A, Marusczyk J, *et al.* "New Publicly Available Chemical Query Language, CSRML, To Support Chemotype Representations for Application to Data Mining and Modeling." J. Chem. Inf. Model. 2015;55(3):510-528.](http://pubs.acs.org/doi/abs/10.1021/ci500667v)

### ChemoTyper application Download

ChemoTyper is available for download for registered users. The new version 1.1 was released in April 2023.

Please [login](/login) if you have already an account or [register](/register).

Chemotype Editor
----------------

The Chemotype Editor is a graphical user interface (GUI) application for creating and editing chemotypes. Substructures and patterns can be sketched using a molecular editor or imported from an external file. Atoms, bonds, molecular annotations, and properties can be added through the GUI application. Edited chemotypes can be saved in the XML-based Chemical Subgraphs and Reactions Mark-up Language (CSRML) and used as structural alerts or chemical fingerprints. The development of the Chemotype Editor received funding from the Innovative Medicines Initiative 2 Joint Undertaking under grant agreement No 777365 ([​eTRANSAFE project](https://etransafe.eu/)) and the Cosmetics Europe Ontology project.

### Chemotype Editor Download

The editor is available for download for registered users: [download Chemotype Editor](# "No permission to file.") and [download tutorial for Chemotype Editor](# "No permission to file.").

Please [login](/login) if you already have an account or [register](/register).

Please note, this implementation of the editor is preliminary. It does not currently support reactions, physicochemical properties of atoms, bonds, and molecules, additional substructures exceptions, and inclusions. Although the CSRML format can handle multiple chemotypes, the editor is limited to a single chemotype at a time. The editor can import SMARTS using copy & paste. However, SMARTS recursive fragments and reactions are not supported.

CSRML Reference Implementation
------------------------------

The Chemical Subgraphs & Reactions Mark-up Language – CSRML – is an XML-based chemical query language. CSRML is a universal media describing chemical (sub)structures and their query attributes for chemical (sub)structure searches. Furthermore, chemical reactions and its transformation rules can be defined. The CSRML standard is targeted to the following purposes and applications.

*   Provide a universal platform for specifying advanced substructure queries
*   Aid developers to create GUI-based editors to create substructure queries in CSRML format
*   Support the community and allow for an easy exchangeability of substructure queries between different programs and databases
*   Encourage developers to create and distribute the CSRML extensions and software

Beside the standard XML Schema Definition that establishes the CSRML data structure and XML syntax, an open-source LGPL-licensed reference library that provides the generic I/O functionality for the CSRML documents has been implemented. The reference library implementation contains modules for the following purposes and applications.

*   Read and parse CSRML documents resulting in programmatic objects representing CSRML elements
*   Write CSRML objects, *e.g.*, into a file
*   Validate CSRML content at a basic level, *e.g.*, for checking syntax and semantic features against the language definition expressed by an XML schema document

Both the XML Schema Definition of CSRML, and the source code of the CSRML reference implementation are released under the [​GNU Lesser General Public License Version 2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) and can be downloaded free-of-charge.

### Reference Implementation Download

The source code of the CSRML reference implementation is available for download for registered users.

Please [login](/login) if you have already an account or [register](/register).

Contact
-------

In technical support issues please contact us through: [​info@chemotyper.org](mailto:info@chemotyper.org)

Acknowledgement
---------------

The ChemoTyper application was developed by Molecular Networks GmbH, Erlangen, Germany under a contract from the U.S. FDA Center for Food Safety and Applied Nutrition (CFSAN), Office of Food Additive Safety. The XML-based substructure (or chemotype) definition language CSRML was co-developed in collaboration with Altamira LLC, Columbus, OH, USA.

Visit the [​website](https://www.mn-am.com) of Molecular Networks GmbH and Altamira LLC.
