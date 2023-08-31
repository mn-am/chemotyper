# chemotyper

Welcome to the ChemoTyper
=========================

The ChemoTyper application
--------------------------

The ChemoTyper application is a tool that allows for searching and highlighting chemical chemotypes (chemical substructures or subgraphs) in datasets of molecules. Typical applications are as following:

*   searching for structural alerts for toxicity in chemical structure files
*   filtering of chemical structures according to chemotypes
*   visualization and inspection of chemotypes
*   grouping of chemicals according to chemotypes, and
*   fingerprinting of chemical structure sets against chemotypes

ChemoTyper includes [​ToxPrint](https://toxprint.org). [​ToxPrint](https://toxprint.org) is a public set of chemotypes developed by Altamira LLC for FDA CFSAN’s CERES project. The [​ToxPrint](https://toxprint.org) contains three basic subsets: generic structural fragments, Ashby-Tennant genotoxic carcinogen rules [​(Ashby, J.; Tennant, R.W., 1988)](http://dx.doi.org/10.1016/0165-1218(88)90114-0), cancer TTC categories [​(Kroes, R. et. al. 2004)](http://dx.doi.org/10.1016/j.fct.2003.08.006).

Publications about ToxPrint chemotypes, CSRML language, and ChemTyper application
---------------------------------------------------------------------------------

*   [​Yang C, Tarkhov A, Marusczyk J, et al. "New Publicly Available Chemical Query Language, CSRML, To Support Chemotype Representations for Application to Data Mining and Modeling." J. Chem. Inf. Model.. 2015;55(3):510-528.](http://pubs.acs.org/doi/abs/10.1021/ci500667v)

### Download the ChemoTyper

ChemoTyper is available for download for registered users. The new version 1.1 was released in April 2023.

Please [login](/login) if you have already an account or [register](/register).

The Chemotype Editor
--------------------

The Chemotype Editor is a graphical user interface (GUI) application for creating and editing chemotypes. Substructures and patterns can be drawn using a molecular editor or imported from an external file. Atoms, bonds, molecular annotations, and properties can be added through the GUI. Edited chemotypes can be saved in the XML-based Chemical Subgraphs and Reactions Mark-up Language (CSRML) and used as alerts or fingerprints. The development of the Chemotype Editor received funding from the Innovative Medicines Initiative 2 Joint Undertaking under grant agreement No 777365 ([​eTRANSAFE project](https://etransafe.eu/)) and the Cosmetics Europe Ontology projects.

### Download the Chemotype Editor

The editor is available for download for registered users: [download Chemotype Editor](# "No permission to file.") and [download tutorial for Chemotype Editor](# "No permission to file.").

Please [login](/login) if you already have an account or [register](/register).

Please note, this implementation of the editor is preliminary. It does not currently support reactions, physicochemical properties of atoms, bonds, and molecules, additional substructures exceptions, and inclusions. Although the CSRML format can handle multiple chemotypes, the editor is limited to a single chemotype at a time. The editor can import SMARTS using copy & paste. However, SMARTS recursive fragments and reactions are not supported.

The CSRML Reference Implementation
----------------------------------

The Chemical Subgraphs & Reactions Mark-up Language – CSRML – is a chemical XML language seen as a universal media describing the chemical (sub)structures and its query attributes, as well as the reactions and the transformations' rules. The CSRML standard is targeted to:

*   provide an universal platform of specifying the advanced substructure queries,
*   aid the developers to create GUI-based editors to input substructure queries in CSRML format,
*   support the community and allow the easy exchangeability of the substructure queries between different programs and databases, and
*   encourage the developers to create and distribute the CSRML extensions and software.

Aside the standard XML Schema Definition that establishes the CSRML data structure and XML syntax, an open-source LGPL-licensed reference library that provides the generic I/O functionality for the CSRML documents has been implemented. The reference library implementation contains modules to:

*   read and parse CSRML documents resulting in the programmatic objects representing the CSRML elements
*   write CSRML objects, e.g., into a file
*   validate CSRML content at the basic level, e.g., for checking syntax and semantic features against the language definition expressed by an XML Schema document

Both the XML Schema Definition of CSRML, and the source code of the CSRML reference implementation are released under the [​GNU Lesser General Public License Version 2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) and can be downloaded free-of-charge.

### Download the Reference Implementation

The source code of the CSRML reference implementation is available for download for registered users.

Please [login](/login) if you have already an account or [register](/register).

Contact
-------

In technical support issues please contact us through: [​info@chemotyper.org](mailto:info@chemotyper.org)

Acknowledgement
---------------

The ChemoTyper application was developed by Molecular Networks GmbH, Erlangen, Germany under a contract from the U.S. FDA, Center for Food Safety and Applied Nutrition (CFSAN), Office of Food Additive Safety. The XML-based substructure (or chemotype) definition language CSRML was co-developed in collaboration with Altamira LLC, Columbus, OH, USA.

Visit the [​website](https://www.mn-am.com) of Molecular Networks GmbH and Altamira LLC.
