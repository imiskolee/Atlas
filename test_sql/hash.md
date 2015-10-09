###

insert into `table_name` (`filed_1`,....) values ("string",....)

select * from `table_name` where shard_key="string";

select * from `table_name` where shard_key="string" limit n,m;

select * from `table_name` where shard_key="string" order by filed_name desc;

select * from `table_name` where shard_key="string" order by filed_name asc;

select * from `table_name` where shard_key="string" order by field_name asc limit n,m;

update `table_name` set field_name="value" where shard_key=string"

update `table_name` set field_name="value" where shard_key=string" and other_filed="xxxx"
