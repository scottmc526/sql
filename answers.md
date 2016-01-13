1. select * from riders join bikes on riders.bicycle_id = bikes.id;

2. select * from riders left join bikes on riders.bicycle_id = bikes.id;

3. select * from riders right join bikes on riders.bicycle_id = bikes.id;

4. select * from riders full outer join bikes on riders.bicycle_id = bikes.id where first_name is null ;

5. select * from riders left join bikes on riders.bicycle_id = bikes.id where riders.bicycle_id is null;

6. select * from riders full outer join bikes on riders.bicycle_id = bikes.id where riders.bicycle_id is null or bikes.id is null;

7. select * from riders full outer join bikes on riders.bicycle_id = bikes.id;
