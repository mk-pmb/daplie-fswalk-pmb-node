
<!--#echo json="package.json" key="name" underline="=" -->
daplie-fswalk-pmb
=================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Maintenance fork of Daplie&#39;s node-walk, a node port of python&#39;s
os.walk.
<!--/#echo -->

For documentation, please refer to the [original repo][orig-repo],
or [my copy thereof][repo-mirror].

Major differences:
  * Dropped the Apache license.
  * Removed some stuff I don't use.
  * Implemented the "nodes" event.
    (Easy one-line change but essential for my script.)


Known issues
------------

* Needs more/better tests and docs.




&nbsp;

  [orig-repo]: https://git.daplie.com/Daplie/node-walk
  [repo-mirror]: https://github.com/mk-pmb/node-walk-daplie

License
-------
<!--#echo json="package.json" key=".license" -->
MIT
<!--/#echo -->
