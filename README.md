# assignment2-chittipolu
# Rohith Chittipolu
### Domino's Pizza
**Domino's pizza** is located on 1006 S Main St. Just across it an hyvee grocery store is located and there is a taco bell outlet just few blocks after domino's pizza. In maryville **Domino's** is located in the middle of other food places like mcdonald's,El Maguey etc. 
---
### Directions to Domino's at Maryville:
1. The closest airport to maryville domino's is **Kansas City International Airport.**
2. After coming out of the airport drive onto the Cookingham Dr for a mile.
3. Then merge onto NW 120th St after driving for half a mile then take exit 13 and continue on I-29 S for almost 44 miles.
4. Now  take the exit on the left onto I-29 S/US-71 S toward US-59 S/Kansas City.
5. After driving for 32 miles you can find Domino's pizza to your left.

Bon appetit!.

### MENU
* **Pizzas:**
    - Chicken taco
    - MeatZZa
    - Philly Cheese Steak
    - Pacific Veggie
    - Cheesy
* **Sandwiches**
    - Buffalo Chicken
    - Chicken Habanero
    - Chicken Bacon Ranch
    - Mediterranean Veggie
* **Desserts**
    - Cinnamon Bread Twists
    - Chocolate Lava Crunch Cakes
    - Domino's Marbled Cookie Brownie
* **Drinks**
    - Coke
    - Diet Coke
    - Sprite
    - Fanta

**[Link to AboutMe](AboutMe.md)**

---
### Sports
Below table contains details about sports.It contains Sport name, location and amount to be paid for equipment.<br>These are the  4 sports that I would recommend someone to try.

|  Name | Location | Amount|
|-------|----------|-------|
|Volley Ball| Hyderabad stadium | $ 20 |
|Soccer| LB nagar Soccer ground | $ 120 |
|Badminton| RGI Court | $ 80 |
|Cricket| Chennai stadium | $ 100  |

---
# Quotes

>Be yourself; everyone else is already taken  _Oscar Wilde_

>“Two things are infinite: the universe and human stupidity; and I'm not sure about the universe.”    _Albert Einstein_

---
### Arbitrary-precision arithmetic addition

>In computer science, arbitrary-precision arithmetic, also called bignum arithmetic, multiple-precision arithmetic, or sometimes infinite-precision arithmetic, indicates that calculations are performed on numbers whose digits of precision are limited only by the available memory of the host system. This contrasts with the faster fixed-precision arithmetic found in most arithmetic logic unit (ALU) hardware, which typically offers between 8 and 64 bits of precision.
Source: <https://en.wikipedia.org/wiki/Arbitrary-precision_arithmetic>

```
int carry = 0;
for (size_t i=0; i<max(a.size(),b.size()) || carry; ++i) {
    if (i == a.size())
        a.push_back (0);
    a[i] += carry + (i < b.size() ? b[i] : 0);
    carry = a[i] >= base;
    if (carry)  a[i] -= base;
}
```
Source: <https://cp-algorithms.com/algebra/big-integer.html>



