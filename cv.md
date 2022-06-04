# [rsschool-cv](адрес "Описание")
# Romanov Ruslan

## Contacts: 
*   ftnewt@gmail.com
*   @Romanov Ruslan#4021
*   Location: Russia, Zelenogorsk (Krasnoyarsk Krai)

## Briefly About Myself:
I work as engineer for sixteen years at Electrical Chemical Plant. I’m responsible, punctual person with communication skills and ability to work in a team. I like studying and get some new knowledge. About two year ago I start learning programming, algorithms and etc., because I want to change my professional field of activity to IT (development, machine learning or something) and I hard working to achieve it.

## Skills:
*   HTML, CSS/less
*   JavaScript(Basic)
*   Git
*   Python –  numpy, pandas, sklearn, Pytorch and etc., packaging and dependency management system (conda, poetry), pytest, black, nox, experiment tracking (MLflow)
*   Windows, Linux(Ubuntu)
*   Figma
*   Editors: Atom, VSCode, PyCharm, Jupiter.

## Code Example:
KATA from CODEWARS:Complete the method which returns the number which is most frequent in the given input array. If there is a tie for most frequent number, return the largest number among them.
```
from collections import Counter
def highest_rank(data):   
    a = set()
    arr = []
    for i in data:
        if i not in a:
            arr.append((i, data.count(i)))
            a.add(i)
    arr1 = [x for x in arr if x[1] == max(arr, key=lambda tup: tup[1])[1]]
    return max(arr1, key=lambda x: x[0])[0]
```

## Education:
*    Tomsk Polytechnic University, Faculty of Physics and Technology, specialist
*    Deep learning school part 1, 2. (CV, NLP) [DLSchool](https://www.dlschool.org/)  
*    The Rolling Scopes School. Introduction to Machine Learning. https://rs.school/machine-learning/

## Experience
*    Capstone ML project https://github.com/N3wBaz/forest_project

## English Upper-intermediate level