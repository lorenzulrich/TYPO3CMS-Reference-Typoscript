.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _cobj-img-resource:

IMG\_RESOURCE
^^^^^^^^^^^^^

Returns only the image-reference, possibly wrapped with stdWrap. May
be used for putting background images in tables or table-rows or to
import an image in your own include-scripts.

The array $GLOBALS['TSFE']->lastImgResourceInfo is set with the info-
array of the resulting image resource (if any) and contains width,
height and so on.

.. ### BEGIN~OF~TABLE ###

.. container:: table-row

   Property
         file

   Data type
         imgResource


.. container:: table-row

   Property
         stdWrap

   Data type
         :ref:`->stdWrap <stdwrap>`


.. ###### END~OF~TABLE ######

[tsref:(cObject).IMG\_RESOURCE]

