# [Command] _storage-mover project delete_

Deletes a Project resource.

## Versions

### [2023-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9wcm9qZWN0cy97fQ==/2023-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/projects/{} 2023-03-01 -->

#### examples

- project delete
    ```bash
        storage-mover project delete -g {rg} --storage-mover-name {mover_name} -n {project_name}
    ```
