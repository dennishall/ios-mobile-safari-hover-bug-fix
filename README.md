ios-mobile-safari-hover-bug-fix
===============================

Fixes the iOS mobile safari hover bug.  A little background: Tablets [generally] don't have "hover".  iOS mobile safari has a *feature* that simulates hover. However, there is a bug in their current implementation (as of August 2013) that manifests itself when there is a group of items that have a hover state defined in css. What happens is that when tapping an item in the group, one of the other items in the group momentarily displays its hover state before the correct one does. This fixes that.
