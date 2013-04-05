
The Changes
===========

v0.1.1
------

1. added the :py:mod:`mosql.json`.
2. added the :py:meth:`mosql.result.Model.customize`.
3. supports using attribute to access :py:class:`~mosql.result.Model`.
4. allows customizing insert, select, update and delete by the class methods of a :py:class:`~mosql.result.Model`.
5. respects the ``column_names`` when do a select.
6. fixed the wrong sql without specifying ``identify_by``.
7. fixed the SQL dumped with None. (issue `#1 <https://github.com/moskytw/mosql/issues/1>`_)