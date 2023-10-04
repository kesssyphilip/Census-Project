# Census-Project
The purpose of such a census is to compare different people across the nation and to
provide the government with accurate statistics of the population to enable better planning, to develop policies,
and to allocate certain funding.
In the project, you will be provided with a mock census of an imaginary modest town. I would like you to
consider yourselves to be part of a local government team who will be making decisions on what to do with an
unoccupied plot of land and what to invest in. To address these questions, you will need to clean and analyse the
mock census data provided.
About this Mock Census.
The mock census you will be given contains randomly generate data using the Faker package in Python. It has
been generated in a similar manner to (and designed to directly emulate the format of) the 1881 census of the
UK wherein only a few questions were asked of the population. The fields recorded are as follows:
1. Street Number (this is set to “1” if it is a unique dwelling);
2. Street Name;
3. First Name of occupant;
4. Surname of occupant;
5. Age of occupant;
6. Relationship to the “Head” of the household (anyone aged over 18 can be a “Head” – they are simply
the person who had the responsibility to fill in the census details);
7. Marital status (one of: Single, Married, Divorced, Widowed, or “NA” in the case of minors);
8. Gender (one of: Male, Female; note that other responses were not implemented in 1881);
9. Occupation (this field was implemented in a modern style, rather than typical 1881 occupations);
10. Infirmity (we have implemented a limited set of infirmities following the style of 1881);
11. Religion (we have implemented a set of real-world religions).
The first task you will have to do is to clean this dataset. As you will rapidly discover, there are missing entries,
and, candidly, some responses from the population are outright lies. Part of the grading for the assignment will
assess these details.
The Task. The town from the census is a modestly sized one sandwiched between two much larger cities that it
is connected to by motorways. The town does not have a university, but students do live in the town and
commute to the nearby cities. Once you have a cleaned dataset to analyse, your task is to decide the following:
(a) What should be built on an unoccupied plot of land that the local government wishes to
develop?
(b) Which one of the following options should be invested in?
