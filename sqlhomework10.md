select * from city 
left join country on city.country_id=country=country_id;

select py.payment_id, cr.first_name, cr.last_name from customer cr
 right join payment py on cr.customer_id = py.customer_id
 
 
select rn.rental_id, cr.first_name, cr.last_name from customer cr
full join rental rn on cr.customer_id = rn.customer_id