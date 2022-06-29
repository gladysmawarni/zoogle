# Zoogle
-------
### Third project @[ironhack](https://www.ironhack.com/en) Data Analytics bootcamp, combining Google Map's API with dataset web scraped from Zomato's website.

The final functioning script is in the [final_code.py](https://github.com/gladysmawarni/zoogle/blob/main/final_code.py).

This project combines Google Maps API function with information of restaurants from Zomato (that is obtained by webscrapping the website using BeautifulSoup and Selenium) to make a program that helps user plan out their food trips in Lisbon.

How it works:
- The program starts by asking the user how many people are joining the trip, and the total budget.
- Asks for the starting point, what kind of food do the user prefer and the area.
![1](https://user-images.githubusercontent.com/78975611/176405615-8c218788-e824-4295-9204-dc824b7a5e74.png)


- Returns information of restaurants in selected area, along with Zomato's rating and estimated price per person.
- After the user selected which restaurant they want, the program calculates the total food cost (multiplied by how many people joining) and the trip cost (calculated by measuring the euclidian distance of the two locations and the gas price).
![2](https://user-images.githubusercontent.com/78975611/176405792-34ee57cf-9fa2-481b-bf06-59946560cdb2.png)

![3](https://user-images.githubusercontent.com/78975611/176405909-be0d2bb3-dcf0-4def-9bde-70fbc2ca987e.png)

![4](https://user-images.githubusercontent.com/78975611/176405936-ed696e1c-32ca-4c0d-a586-7351ebed5898.png)

- The program ends after the user selected 4 places they want to go.
- And return a table of information (name of the restaurant, total price per restaurant, and total price of all).

![5](https://user-images.githubusercontent.com/78975611/176405980-c6593b7a-d6d9-4783-91f3-8afb191094aa.png)



