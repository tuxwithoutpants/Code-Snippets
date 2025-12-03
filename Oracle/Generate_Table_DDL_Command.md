#### Generate Table DDL Command
<i> Generate Table DDL Command </i> 

`set long 100000`
`set pagesize 0 ;`
`set linesize 1000;` 
`set feedback off ;`
`set verify off ;`
`set trimspool on;`
``
`SELECT DBMS_METADATA.get_ddl ('TABLE', 'EMPLOYEES','HR') from dual;`
