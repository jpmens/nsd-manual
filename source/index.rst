.. _doc_nsd:

.. Warning:: This project has the goal to replace the `existing documentation
             <https://www.nlnetlabs.nl/documentation/nsd/>`_ with an
             open source community project. **This is a work in progress.**

Name Server Daemon (NSD) by NLnet Labs
======================================

Welcome to the documentation of the NLnet Labs Name Server Daemon (NSD), an
authoritative DNS name server. It has been developed for operations in
environments where speed, reliability, stability and security are of high
importance.

NSD has a pure design philosophy that prioritises raw performance. This means
that if you serve hundreds of thousands or even millions of queries per second,
NSD is the leading implementation in the world. This authoritative DNS name
server strives to be a reference implementation for emerging standards of the
Internet Engineering Task Force (IETF). NSD is distributed free of charge in
open source form under the BSD license. For most platforms, packages are
available. 

This documentation is an open source project maintained by NLnet Labs. is edited
via text files in the `reStructuredText
<http://www.sphinx-doc.org/en/stable/rest.html>`_ markup language and then
compiled into a static website/offline document using the open source `Sphinx
<http://www.sphinx-doc.org>`_ and `ReadTheDocs <https://readthedocs.org/>`_
tools.

We always appreciate your feedback and improvements. You can submit an issue or
pull request on the `GitHub repository
<https://github.com/NLnetLabs/nsd-manual/issues>`_, or post a message on the
`NSD users <https://lists.nlnetlabs.nl/mailman/listinfo/nsd-users>`_ mailing
list. All the contents are under the permissive Creative Commons Attribution 3.0
(`CC-BY 3.0 <https://creativecommons.org/licenses/by/3.0/>`_) license, with
attribution to NLnet Labs.


.. toctree::
   :maxdepth: 2
   :name: toc-nsd

   installation
   configuration
   tuning
.. history
.. authors
.. license
