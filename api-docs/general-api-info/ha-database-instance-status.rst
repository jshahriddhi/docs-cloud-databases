.. _cdb-dg-generalapi-dbinstance:

========================
HA Database instance status
========================

When performing actions on a high availability database group, the following cluster status values are possible:

-  BUILD – The HA Group is being created.

-  ACTIVE - The HA Group was successfully created (Source/Replica(s)/Load Balancers ACTIVE).

-  BACKUP - The HA Group is being backed up. (The database instance part of the HA group being backed up will also be in BACKUP state).

-  ADDING\_REPLICA - A new replica instance is being added to the HA Group.

-  REMOVING\_REPLICA - A replica instance is being removed from the HA Group.

-  RESTART\_REQUIRED - A change has occurred to the configuration of instances part of the HA Group that requires the HA Group to be restarted at the user’s convenience.

-  REBOOT - The database instances part of the HA Group are being rebooted.

-  DELETING - The HA Group is being deleted.

-  DELETED - The HA Group has been deleted.

-  RESIZING\_VOLUME - The volume of all instances part of the HA Group is being resized.

-  RESIZING\_FLAVOR - The RAM of all instances part of the HA Group is being resized.

-  FORCING\_FAILOVER - An admin user has triggered a force failover on the HA Group to promote an existing replica to be the new source.

-  DISABLING\_FAILOVER - Failover is being disabled on the HA Group (initiated via an admin user).

-  ENABLING\_FAILOVER - Failover is being re-enabled on the HA Group (initiated via an admin user).

-  FAILOVER\_DISABLED - Failover is currently disabled on the HA Group.

-  UPDATING\_PROXY\_NODES - The Load Balancer nodes part of the HA Group are being re-configured (initiated via an admin user).

-  ERROR - The HA Group failed to build successfully.

-  ADD\_REPLICA\_FAIL - There was a failure adding a replica instance to the HA Group.

-  REMOVE\_REPLICA\_ERROR - There was a failure removing a replica from the HA Group.

-  DELETION\-ERROR - There was a failure deleting the HA Group.

-  UPDATE\_PROXY\_NODES\_ERROR - There was a failure reconfiguring the load balancers part of the HA Group.

-  REPLICATION\_ERROR - The replication is broken between source/replica(s) in the HA Group. The replica instance with broken replication will also report this state.

-  HA\_FAILOVER - A failover has occurred on the HA Group.

-  RESIZE\_FLAVOR\_ERROR - There was a failure resizing the flavor/RAM of the HA Group.

-  VOLUME\_RESIZE\_ERROR - There was a failure resizing the volume of the HA Group.
