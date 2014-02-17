inkScope
========

**Inkscope** is  a [Ceph](http://ceph.com) admin and supervision interface. It  relies on a nosql solution. We use  mongodb to store real time metrics and history metrics but not on the same collection. Each collection is ruled by a TTL.

The main folders are:

**documentation** contains diagram of inkScope architecture, datamodel and screenshots

**inkscopeAdm** : GUI for management  of a ceph cluster

**inkscopeCtrl** : server part for inkscopeAdm and inkscopeViz

**inkscopeProbe** : for collect information about the cluster (Ceph and system info)

**inkscopeViz** : to visualize Ceph cluster status and and relations between Ceph cluster objects

**inkscopeMonitor** : for supervision of Ceph
