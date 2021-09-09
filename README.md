# assignment2_Bantu

# Varun Kumar Bantu
###### Goa

There are so many **beaches** in Goa and it is located in **India** and we can enjoy there.

#TravelInfo

---

1. First go to a flight ticket booking website and book a ticket from chicago inernational airport(ORD) to Mumbai.
    1. Rent a car in Maryville to travel to Kansas city Airport.
        1. Then go to kansas city airport(MCI).
        2. Buy a ticket from kansas city airport(MCI) to chicago international airport(ORD).
2. After boarding the flight in kansas airport you will be arrived in chicago airport.
    1. Then board the flight in chicago international terminal and you will be arrived in Mumbai airport.
    2. Buy a ticket to GOA and and board the flight.
* After boarding the flight in Mumbai Airpoprt you will be landed in Goa airport.
    * Then look for a cab after landing in the airport.
        * Ask the driver to take you to a resort.
        *Then book a room in resort and then fresh up.
* After getting ready then you are ready to experinece the beauty of Goa beaches.
   * Go to famous beaches like Baga and Agoda etc.
   * Enjoy Sea food in Goa which is completley unique.
   * Visit historical places like forts and monuments which had a great history.

**[In README](AboutMe.md)**    

# Famous Foods In Hyderabad

---

The following table consists some of most famous foods that are available in Hyderabad.

| Food Item | Loaction | Price |
| --- | --- | --- |
| Chicken Biryani | Oneplace KPHB | $10 |
| Barbeque chicken | Ab's Jublee Hills | $15 |
| Mandi Chicken & Mutton | Arabian Mandi | $12 |
| Butter Ghee Dosa | RamKiBandi | $4 |






# Inspirational Quotes

---

> “Be yourself everyone else is already taken.”
>> ―*Oscar Wilde*
>
> “All our dreams can come true, if we have the courage to pursue them.”
>> –*Walt Disney*


# Code Fencing

---

> A randomized heap is a heap that, by using a random number generator, allows you to perform all the necessary operations in the logarithmic expected time.<br>

> A heap is a binary tree, for any vertex of which it is true that the value at this vertex is less than or equal to the values ​​in all its descendants. 

<https://titanwolf.org/Network/Article/Randomized%20Heap>

We can immediately describe the structure of the binary heap:
```
struct Tree {
    int value;
    Tree * l = nullptr;
    Tree * r = nullptr;
};
Tree* merge(Tree* t1, Tree* t2) {
    if (!t1 || !t2)
        return t1 ? t1 : t2;
    if (t2->value < t1->value)
        swap(t1, t2);
    if (rand() & 1)
        swap(t1->l, t1->r);
    t1->l = merge(t1->l, t2);
    return t1;
}
```
<https://cp-algorithms.com/data_structures/randomized_heap.html>

