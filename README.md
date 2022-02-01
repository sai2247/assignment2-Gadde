# assignment2-Gadde
Sai krishna Gadde
# Sai Krishna Gadde
###### subhani biryani's
 This place is located in **Guntur** in **Andhra pradesh** district has lot variety of biryanis it has many branches located in Guntur 
 ---------------------------------------------------------------------------------------------------------------------------------------------------
 # Vijayawada Airport is closest airport to my food location
 From subhani biryani hotel the Guntur bus stand is 10 min drive

take the bus of number 428

get down the bus at guntur bustand

take uber and go to vijayawada bus stand , there you can find direct cabs and autos to the airport

#### some food items
* Chicken Biryani
* Mutton Biryani
* Shrimp Biryani
* Paneer Biryani

[Know me](https://github.com/sai2247/assignment2-Gadde/blob/main/AboutMe.md#sai-krishna-gadde)

-----------------------------------------------

# Sports

volleyball, Badminton, Cricket and Tennis are the sports which I would like to recommend to anyone, who is intrested in some physical activity.

|  Name       |  Location      | Amount|
|-------------|----------------|-------|
|  volleyball | campus ground  |  $50  |
|  Badminton  | Recreation     |  $35  |
|  Cricket    | Hughes         |  $50  |
|   Tennis    |  Recreation    |  $55  |

----------------------------------------------------

# Quotes

> "We are such stuff as dreams are made on, and our one little life is rounded with a sleep." - *William Shakespeare*

>  But soft! What light through yonder window breaks? It is the east, and Juliet is the sun." -*William Shakespeare*

-------------------------------------------------------------

# Oriented Area of a Triangle: The Formula

>There are formulas for the area of a triangle in terms of the coordinates of the vertices that automatically give the algebraic area. For example, to find the algebraic area of a triangle with first vertex at (0, 0), second vertex at (a, b) and third vertex at (c, d), we may use the formula (1/2)(ad - bc). This will be positive if the slope d/c of the line from (0, 0) through (c, d) is greater than the slope b/a of the line from (0, 0) through (a, b), since d/c > b/a implies that ad > bc and ad - bc > 0. In terms of vectors, if the line along (a, b) rotates in a counterclockwise direction to get to the line along (c, d), then the triangle from (0, 0) to (a, b) to (c, d) has positive area, and if it rotates in a clockwise direction, the algebraic area of the triangle is negative.

To Know More (https://www.techhouse.org/~mdp/midpoint/oriented1.php)

````
int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}
````
CP-Algorithm: (https://cp-algorithms.com/geometry/oriented-triangle-area.html)
