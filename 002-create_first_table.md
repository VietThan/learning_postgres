```sql
begin;
create table if not exists provinces_test (
	int_province_key integer,
	int_ver integer,
	int_ver_last integer,
	PRIMARY KEY (int_province_key, int_ver),
	txt_province_name text,
	txt_province_type text,
	txt_province_service_key text,
	txt_province_service_order text
);
commit;
```