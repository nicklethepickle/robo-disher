# robo-disher
Code for the Robo-Disher: a robot that does the dishes.

DISCLAIMER: The Robo-Disher requires a dish rack above the sink and a rack for the cleaning utilities (soap, iron wool, etc.)
This repository is for the code of my new invention: the Robo-Disher. The Robo-Disher (RD for short) will take in a dish, take photos from different angles (90° or directly above for plates & utensils, and 45° for bowls and cups) and compare the 90° photo to all images of dirty plates and utensils in the database, while comparing the 45° photo to all images of dirty bowls and cups. If any of them have a 30% or more match, it will scrub or rinse according to the type of dish. Once the dish has a 75% or more match with the clean dish photos, it will move the current dish to the rack and get the next dish.
