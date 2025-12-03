#### Generate Table DDL Command
<i> Generate Table DDL Command </i> 

`set long 100000`<br>
`set pagesize 0 ;`<br>
`set linesize 1000;`<br> 
`set feedback off ;`<br>
`set verify off ;`<br>
`set trimspool on;`<br><br>

`SELECT DBMS_METADATA.get_ddl ('TABLE', '<<TABLE>>','<<SCHEME>>') from dual;`
