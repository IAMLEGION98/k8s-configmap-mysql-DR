# Using Kubernetes ConfigMaps to setup Backup and Restore for a MySQL Database Container



 
- *mysqldb-plain* - To deploy vanilla mysqldb

- *mysqldb-with-DR* - To deploy mysqlDB with Backup Restore functionality
    
## To Deploy    

```bash
kubectl apply -f <folder_name>
```
    
> Important: Make sure Persistent Volume's are properly setup as per the `pv.yaml` prior to deployment.



//TO-DO: Further instructions