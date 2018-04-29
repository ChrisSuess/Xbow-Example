Xbow-Example
~~~~~~~~~~~~~

An example Amber job for use with Xbow and Xflow

Example **Xbow** Job
~~~~~~~~~~~~~~~~~~~~

1. Download an example from the link below::

``wget https://github.com/ChrisSuess/Xbow-Example/archive/master.zip && unzip master.zip``

2. Create a **Xbow** cluster::

``xbow-create_cluster``

3. Navigate to the directory containing the example files. Sync the data with **Xbow** cluster::

``xbow-sync``

4. Login to your **Xbow** cluster::

``xbow-login``

5. Navigate to the directory containing the example files::

``cd shared/$Example_files``

6. Using **Xflow** run the example::

``xflow-exec csh run.dhfr`` 

7. Log off **Xbow** cluster::

``ctrl + d``

8. Sync the data back from the **Xbow** cluster::

``xbow-sync``

9. Delete the cluster::

``xbow-delete_cluster``
