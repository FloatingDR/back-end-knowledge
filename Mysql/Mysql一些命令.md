1. 查看 binlog 格式

   ```sql
   show variables like 'binlog_format';
   ```

2. 查看 binlog 内容

   ```sql
   show binlog events in 'master-bin.000003';
   ```