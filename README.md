# HomeWorkMysql-07.10.2024


USE Airport;


SELECT * 
FROM clients 
WHERE age > 40;



SELECT * 
FROM clients 
WHERE name LIKE '%Egor%';



SELECT * 
FROM tickets 
WHERE service_class IN ('Economy', 'PremiumEconomy') AND price > 40000;



SELECT departure, arrival 
FROM trips 
WHERE status IN ('Cancelled', 'Delayed');



SELECT * 
FROM clients 
ORDER BY name ASC;



SELECT * 
FROM clients 
ORDER BY age DESC;




SELECT * 
FROM tickets 
WHERE service_class != 'Economy' 
ORDER BY price DESC;
