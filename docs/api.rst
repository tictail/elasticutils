.. _api-docs-chapter:

==========
 API docs
==========

.. contents::
   :local:


The S class
===========

.. autoclass:: elasticutils.S

   .. automethod:: elasticutils.S.__init__

   **Chaining transforms**

       .. automethod:: elasticutils.S.query

       .. automethod:: elasticutils.S.query_raw

       .. automethod:: elasticutils.S.filter

       .. automethod:: elasticutils.S.order_by

       .. automethod:: elasticutils.S.boost

       .. automethod:: elasticutils.S.demote

       .. automethod:: elasticutils.S.facet

       .. automethod:: elasticutils.S.facet_raw

       .. automethod:: elasticutils.S.highlight

       .. automethod:: elasticutils.S.values_list

       .. automethod:: elasticutils.S.values_dict

       .. automethod:: elasticutils.S.es

       .. automethod:: elasticutils.S.indexes

       .. automethod:: elasticutils.S.doctypes

       .. automethod:: elasticutils.S.explain

   **Methods to override if you need different behavior**

       .. automethod:: elasticutils.S.get_es

       .. automethod:: elasticutils.S.get_indexes

       .. automethod:: elasticutils.S.get_doctypes

   **Methods that force evaluation**

       .. automethod:: elasticutils.S.__iter__

       .. automethod:: elasticutils.S.__len__

       .. automethod:: elasticutils.S.all

       .. automethod:: elasticutils.S.count

       .. automethod:: elasticutils.S.execute

       .. automethod:: elasticutils.S.facet_counts


The F class
===========

.. autoclass:: elasticutils.F
   :members:


The MappingType class
=====================

.. autoclass:: elasticutils.MappingType

   .. automethod:: elasticutils.MappingType.from_results

   .. automethod:: elasticutils.MappingType.get_object

   .. automethod:: elasticutils.MappingType.get_index

   .. automethod:: elasticutils.MappingType.get_mapping_type_name

   .. automethod:: elasticutils.MappingType.get_model


The SearchResults class
=======================

.. autoclass:: elasticutils.SearchResults
   :members:


The MLT class
=============

.. autoclass:: elasticutils.MLT
   :members:

   .. automethod:: elasticutils.MLT.__init__