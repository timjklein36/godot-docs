:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualScriptSequence.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualScriptSequence:

VisualScriptSequence
====================

**Inherits:** :ref:`VisualScriptNode<class_VisualScriptNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Executes a series of Sequence ports.

Description
-----------

Steps through a series of one or more output Sequence ports. The ``current`` data port outputs the currently executing item.

**Input Ports:**

- Sequence: ``in order``

**Output Ports:**

- Sequence: ``1``

- Sequence: ``2 - n`` (optional)

- Data (int): ``current``

Properties
----------

+-----------------------+---------------------------------------------------------+-------+
| :ref:`int<class_int>` | :ref:`steps<class_VisualScriptSequence_property_steps>` | ``1`` |
+-----------------------+---------------------------------------------------------+-------+

Property Descriptions
---------------------

.. _class_VisualScriptSequence_property_steps:

- :ref:`int<class_int>` **steps**

+-----------+------------------+
| *Default* | ``1``            |
+-----------+------------------+
| *Setter*  | set_steps(value) |
+-----------+------------------+
| *Getter*  | get_steps()      |
+-----------+------------------+

The number of steps in the sequence.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
