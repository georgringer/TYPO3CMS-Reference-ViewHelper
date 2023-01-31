.. include:: /Includes.rst.txt

.. _typo3-fluid-form-countryselect:

==================
form.countrySelect
==================


Renders an :html:`<select>` tag with all available countries as options.

Examples
========

Example::

   <f:form.countrySelect name="country" value="{defaultCountry}" />

Output::

   <select name="country">
     <option value="BE">Belgium</option>
     <option value="FR">France</option>
     ....
    </select>

You can also use the "property" attribute if you have bound an object to the form.
See :ref:`<f:form> <typo3-fluid-form>` for more documentation.

Arguments
=========


.. _form.countryselect_additionalattributes:

additionalAttributes
--------------------

:aspect:`DataType`
   mixed

:aspect:`Required`
   false
:aspect:`Description`
   Additional tag attributes. They will be added directly to the resulting HTML tag.

.. _form.countryselect_data:

data
----

:aspect:`DataType`
   mixed

:aspect:`Required`
   false
:aspect:`Description`
   Additional data-* attributes. They will each be added with a "data-" prefix.

.. _form.countryselect_aria:

aria
----

:aspect:`DataType`
   mixed

:aspect:`Required`
   false
:aspect:`Description`
   Additional aria-* attributes. They will each be added with a "aria-" prefix.

.. _form.countryselect_name:

name
----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Name of input tag

.. _form.countryselect_value:

value
-----

:aspect:`DataType`
   mixed

:aspect:`Required`
   false
:aspect:`Description`
   Value of input tag

.. _form.countryselect_property:

property
--------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Name of Object Property. If used in conjunction with <f:form object="...">, "name" and "value" properties will be ignored.

.. _form.countryselect_class:

class
-----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   CSS class(es) for this element

.. _form.countryselect_dir:

dir
---

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Text direction for this HTML element. Allowed strings: "ltr" (left to right), "rtl" (right to left)

.. _form.countryselect_id:

id
--

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Unique (in this file) identifier for this HTML element.

.. _form.countryselect_lang:

lang
----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Language for this element. Use short names specified in RFC 1766

.. _form.countryselect_style:

style
-----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Individual CSS styles for this element

.. _form.countryselect_title:

title
-----

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Tooltip text of element

.. _form.countryselect_accesskey:

accesskey
---------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Keyboard shortcut to access this element

.. _form.countryselect_tabindex:

tabindex
--------

:aspect:`DataType`
   integer

:aspect:`Required`
   false
:aspect:`Description`
   Specifies the tab order of this element

.. _form.countryselect_onclick:

onclick
-------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   JavaScript evaluated for the onclick event

.. _form.countryselect_disabled:

disabled
--------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   Specifies that the input element should be disabled when the page loads

.. _form.countryselect_excludecountries:

excludeCountries
----------------

:aspect:`DataType`
   mixed

:aspect:`Default`
   array ()

:aspect:`Required`
   false
:aspect:`Description`
   Array with country codes that should not be shown.

.. _form.countryselect_onlycountries:

onlyCountries
-------------

:aspect:`DataType`
   mixed

:aspect:`Default`
   array ()

:aspect:`Required`
   false
:aspect:`Description`
   If set, only the country codes in the list are rendered.

.. _form.countryselect_optionlabelfield:

optionLabelField
----------------

:aspect:`DataType`
   string

:aspect:`Default`
   'localizedName'

:aspect:`Required`
   false
:aspect:`Description`
   If specified, will call the appropriate getter on each object to determine the label. Use "name", "localizedName", "officialName" or "localizedOfficialName"

.. _form.countryselect_sortbyoptionlabel:

sortByOptionLabel
-----------------

:aspect:`DataType`
   boolean

:aspect:`Required`
   false
:aspect:`Description`
   If true, List will be sorted by label.

.. _form.countryselect_errorclass:

errorClass
----------

:aspect:`DataType`
   string

:aspect:`Default`
   'f3-form-error'

:aspect:`Required`
   false
:aspect:`Description`
   CSS class to set if there are errors for this ViewHelper

.. _form.countryselect_prependoptionlabel:

prependOptionLabel
------------------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   If specified, will provide an option at first position with the specified label.

.. _form.countryselect_prependoptionvalue:

prependOptionValue
------------------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   If specified, will provide an option at first position with the specified value.

.. _form.countryselect_prioritizedcountries:

prioritizedCountries
--------------------

:aspect:`DataType`
   mixed

:aspect:`Default`
   array ()

:aspect:`Required`
   false
:aspect:`Description`
   A list of country codes which should be listed on top of the list.

.. _form.countryselect_alternativelanguage:

alternativeLanguage
-------------------

:aspect:`DataType`
   string

:aspect:`Required`
   false
:aspect:`Description`
   If specified, the country list will be shown in the given language.

.. _form.countryselect_required:

required
--------

:aspect:`DataType`
   boolean

:aspect:`Required`
   false
:aspect:`Description`
   If set no empty value is allowed.
