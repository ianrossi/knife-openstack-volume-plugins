These knife plugins will allow you to do

```knife openstack snapshot list```

and

```knife openstack server create```

using a volume snapshot.

This is especially handy in Openstack deployments where images and image snapshots are not used in favor of volumes backed by Ceph.

If you place these in

```.chef/plugins/knife```

these commands will be added to knife-openstack.
