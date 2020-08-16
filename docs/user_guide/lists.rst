.. _lists:

Lists
=====
A powerful feature of the InterMine framework is the analysis of features lists e.g genes or proteins. Users can store gene lists for example and list of differentially expressed genes from a specific RNASeq experiment then performing GO-term enrichment analysis on such lists.

Creating Lists
~~~~~~~~~~~~~~
The list tool searches the database for the list items and attempts to convert each identifier to the selected type. User can create list from  **Quick List** box on the home page or by clicking on the **Lists** tab from the menu to access the full list upload as seen in :numref:`list_upload`.

.. _list_upload:
.. figure:: images/list_upload.png
  :width: 696
  :alt: List upload form
  :figclass: align-center

  List upload tool

  ..

Creating list example
-------
As an example, enter the following identifiers (comma-separated):
::

      ASH1, CAL0000174561, FTR1,CAS1,CR_08980C_A

Leave the **Select Type** as "Gene" and **Organism** drop-down as "Any". Then click **Create List**. A Summary table is displayed with the results of searching for each of the five identifiers in the list :numref:`list_results`.

.. _list_results:
.. figure:: images/list_results.png
  :width: 696
  :alt: Example: Search results for list of five identifiers
  :figclass: align-center

  Example: Search results for list of five identifiers

  ..

Next, click **Save a list of 5 Genes**. A **List Analysis** page is presented that contains widgets allowing users to perform analyses on the genes in the list.

.. _list_analysis:
.. figure:: images/list_analysis.png
  :width: 696
  :alt: Example: List analysis for gene list
  :figclass: align-center

  Example: List analysis for gene list

  ..

The available widgets are:

* Chromosome Distribution.
* Gene Ontology Enrichment.
* Protein Domain Enrichment.
    * Domains from Proteins 
    * Predicted Domains from genes. 
* Phenotypes (APO). 
* Pathway Enrichment.
* Publication Enrichment.

The selection of widgets provided on the List Analysis page depend on the contents of the list.

  ..

Saving Lists
~~~~~~~~~~~~

Saved lists appear under the **View** tab on the Lists page. For users who are not logged in, lists are saved temporarily; users must log in to save lists permanently. Saved lists may also be accessed from the **MyMine** menu item.

Predefined lists of all genes from different species are also available on the Lists page for all users.

.. figure:: images/saved_lists.png
  :width: 696
  :alt: Saved lists. Lists belonging to user are highlighted.
  :figclass: align-center

  Saved lists. Lists belonging to user are highlighted.

  ..
