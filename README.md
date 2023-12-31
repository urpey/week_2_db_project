# Cantek week 2 SQL project

# ER Diagram
![image](https://github.com/urpey/week_2_db_project/assets/111271561/0e3d7838-3552-44d3-b48b-b8daf0dc7315)

# Query 1
- To Find out the highest-revenue film 
- The query joins the film, inventory, rental, and payment tables to calculate the total revenue for each film. It groups by film title, orders by total revenue descending, and limits to the top 10 films.
- <img width="218" alt="截圖 2023-09-12 上午3 15 53" src="https://github.com/urpey/week_2_db_project/assets/111271561/a2bbde4c-3e0d-4ebc-a95e-1686d9930466">
- The result set shows the top 10 films ranked by total revenue generated. "Telegraph Voyage" had the highest revenue at $215.75, and "Zorro Ark" was the second at $199.72.
  
# Query 2
- To find out the film rented by the most customers 
- The query joins film, inventory, rental, and customer tables to count unique customers per film. It groups by title, orders by customer count descending, and limits to the top 10.
- <img width="260" alt="截圖 2023-09-12 上午3 17 19" src="https://github.com/urpey/week_2_db_project/assets/111271561/1303873f-f284-455a-be89-e5a32acda690">
- The result set shows the top 10 films ranked by number of renters. "Bucket Brotherhood" had the most customers at 34, "Rocketeer Mother" was the second most at 33.
  
# Query 3
- To find out the film that has been rented for the longest time
- The query joins film, inventory, and rental tables to sum the total rental duration per film. It groups by title, orders by total time descending, and limits to the top 10 films.
- <img width="281" alt="截圖 2023-09-12 上午3 21 36" src="https://github.com/urpey/week_2_db_project/assets/111271561/1ee5792b-1746-4944-af47-6049ac0f8081">
- The result set shows the top 10 films ranked by longest total rental time. "Ridgemont Submarine" had the longest time at 173 days, "Gleaming Jawbreaker" was second at 166 days.

# Query 4
- To find out the most popular actor
- The query joins actor, film_actor, and film tables to count films per actor. It concats first and last names to show the actor's full name, groups by actor name, orders by film count descending, and limits to the top 10.
- <img width="194" alt="截圖 2023-09-12 上午3 18 32" src="https://github.com/urpey/week_2_db_project/assets/111271561/39157d2d-8767-4567-8897-de935232ded3">
- The result set shows the top 10 actors ranked by most films acted in. Susan Davis acted in the most films with 54 films, Gina Degeneres was second with 42 films.
  
# Query 5
- To find out the busiest store
- The query joins store, address, inventory, rental, and payment tables to sum revenue per store. It groups by store_id and address, orders by total revenue descending.
- <img width="303" alt="截圖 2023-09-12 上午3 18 58" src="https://github.com/urpey/week_2_db_project/assets/111271561/0e567154-6f7d-4841-9bac-4ddc82aa69ce">
- The result shows store 2 at "28 MySQL Boulevard" had the highest total revenue at $30683.13. Store 1 at "47 MySakila Drive" was second highest at $30628.91.


