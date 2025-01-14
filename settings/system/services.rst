Services
********

Image Service
   Defines the backend for user and organization image lookups.

   Default: ``Zammad Image Service`` (active)

      .. hint::

         On premise installations behind restrictive firewalls require
         ``HTTPS`` access to ``images.zammad.com``.

Geo Calendar Service
   Defines the backend for geo calendar lookups. Used for initial calendar
   succession.

   Default: ``Zammad GeoCalendar Service`` (active)

   .. include:: /settings/system/services.include.rst

Geo IP Service
   Defines the backend for geo IP lookups. Shows also location of an IP address
   if an IP address is shown.

   Default: ``Zammad GeoIP Service`` (active)

   .. include:: /settings/system/services.include.rst

Geo Location Service
   Defines the backend for geo location lookups to store geo locations for
   addresses.

   Default: ``Geo Location Service`` (active)

.. hint:: 

   You can find a detailed privacy information on what we store for how long on
   our `Privacy Appendix`_ inside of our System-Administrator-Documentation.

.. _Privacy Appendix: https://docs.zammad.org/en/latest/appendix/privacy.html
