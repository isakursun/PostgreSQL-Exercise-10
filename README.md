1. SELECT city.city, country.country FROM city
   LEFT JOIN country ON city.country_id = country.country_id;

    ![](./images/1.png)

2. SELECT customer.first_name, customer.last_name FROM payment
   RIGHT JOIN customer ON payment.customer_id = customer.customer_id;

    ![](./images/2.png)

3. SELECT customer.first_name, customer.last_name FROM customer
   FULL JOIN rental ON customer.customer_id = rental.customer_id;

    ![](./images/3.png)