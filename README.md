# Zoogle
-------
### Third project @[ironhack](https://www.ironhack.com/en) Data Analytics bootcamp, combining Google Map's API with dataset web scraped from Zomato's website.

The final functioning script is in the [final_code.py](https://github.com/gladysmawarni/zoogle/blob/main/final_code.py).

This project combines Google Maps API function with information of restaurants from Zomato (that is obtained by webscrapping the website using BeautifulSoup and Selenium) to make a program that helps user plan out their food trips in Lisbon.

How it works:
- The program starts by asking the user how many people are joining the trip, and the total budget.
- Asks for the starting point, what kind of food do the user prefer and the area.
- Returns information of restaurants in selected area, along with Zomato's rating and estimated price per person.
- After the user selected which restaurant they want, the program calculates the total food cost (multiplied by how many people joining) and the trip cost (calculated by measuring the euclidian distance of the two locations and the gas price).
- The program ends after the user selected 4 places they want to go.
- And return a table of information (name of the restaurant, total price per restaurant, and total price of all).


