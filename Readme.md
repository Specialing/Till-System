Brief Specification

1. Different users who work there - they select their name then process the order
2. All the different drinks with room for additions and remvoing from the list
3. Spirits be on one page etc.. Main page have the typical orders, with splashs and mixers
4. Adding the total cost displaying the corrct change to give.
5. Able to remove a drink from an order if there is a mistake
6. Able to make a tab, store the drinks, and cost to be paid later
7. Quick change buttons??? i.e. drink costs 3.80 punter gives £20.. have a button for notes -- give correct change
8. Touch screen
9. Able to be used with card readers (dont even know where to start with this one)
10. Coherent GUI legible colours, shouldnt have multiple pages for a type of drink -- Possibly JavaFX ??
11. Shouldnt take long to load up. Easy to be modified and be easy to build for a bigger company (sql suppport??)
12. No need for login details, just a user selects their name
13. A way to type in the amount given from the punter, or an exact amount button

Shift start -> input float amount
End of day -> end shift and give totals to see if till is up/down
Drink selection screen (with sub screens)
User selection screen or bit on the side (should be done with either fobs or passwords)
Cash up screen showing price, ability to key in custom change, set notes, and credit card transactions, shows change to give
Ability to remove items from basket - (log these against user?)
Management user options to customize buttons
Buttons -> Drink  all drinks stored in backend to retreive info for cashup screen? or just buttons hold all info needed eg button in grid position 1-1 name 'Fosters' colour 'orange' price '2.95'

Naming conventions:
Packages: All lower case eg com.bar.till
Classes: Capitalized eg BarClient
Interfaces: Capitalized
Methods: camelCase
Varialbes: camelCase, should not start with _ or $, short yet meaningful
Constants: UPPERCASE

