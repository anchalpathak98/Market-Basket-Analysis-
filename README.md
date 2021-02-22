#Market basket analysis basically uses three diferent matrix
#1.Support 2. Confidence and 3. Lift.
#Support= It gives a fraction of records which contains factor the factor can be either one or multiple basically support tells us about the frequent combination of factors.

#Support = No of records per transactions containing factors (A,b or both ab)/No of total records.

#Confidence = No of records containing both a and b/No of records containing A.(Confidence tells us about how often factors a and b occur together given no of times A occurs)

#Eg - Suppose A is bread and B is butter the value of confidence will depict the number of records when bread and butter were together purchased/ When bread alone was purchased.

##Lift =It indicates the strength of the role over the random occurence of A and B . The greater the value of lift the more is the strength.
#If Lift is less than 1 it means that there is no association.

#If lift is equal to 1 this means that there is a very poor association.

#If lift is greater than 1 that means it is a good association.

#If lift is equal to 3 it means that if u buy A chances of buying B is three times .

#lift = Support of X union Y / Support of X * Support of Y
