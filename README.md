# algorithm2
Question1:



The given algorithm, FindDistinctElements, calculates the distinct elements present in two sets, set1 and set2, and returns a set containing these distinct elements. It employs a new Set() data structure to store unique elements and loops through each element in both sets. For each element encountered, it adds the element to the distinctElements set, ensuring that only unique elements are included. Finally, the algorithm returns the set of distinct elements.

After calling the FindDistinctElements algorithm with the provided sets set1 and set2, the distinct elements present in both sets are displayed using the Display statement.





Question2:


Dot Product Calculation (dot_product algorithm): This algorithm calculates the dot product of two vectors v1 and v2 of length n. It uses a loop to iterate through the elements of the vectors and calculates the dot product by summing the products of corresponding elements. The calculated dot product is returned.

Orthogonality Check (AreVectorsOrthogonal algorithm): This algorithm determines whether two vectors v1 and v2 are orthogonal by calling the dot_product algorithm. It calculates the dot product of the vectors using the previously defined dot_product algorithm. If the dot product is zero, it indicates that the vectors are orthogonal, and the algorithm returns "Orthogonal." Otherwise, it returns "Not Orthogonal."

The algorithm then prompts the user to input the number of vector pairs n. It iterates through each vector pair, reading the elements of v1 and v2, calculating their orthogonality status using the AreVectorsOrthogonal algorithm, and displaying the result.

