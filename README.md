# 2048game_HW1
You can enjoy the taste of defeat by computer like I do writting the code 
# You can install project in .ipynb format and upload in Google Collaboratory
# How to use:
Firstly run all codes to initiate all lybraries and funcs
After running the last code you will receive a pole in which you can launch commands,
there are 4 commands:
- 1 is for shifting your numbers to the left
- 2 is for shifting your numbers up
- 3 is for shifting your numbers to the right
- 4 is for shifting your numbers down
You need to acheive the maximal score, which is shown to you after each step
# Functions used:
Made with the help of the libraries cupy & random.
Functions that used:.
draw_pole - to make the pole with symbols.
new_value - create a random value, import from random library.
The value equial 2 will appear on the clear cell with probability 90% and 4 will appear with probability 10%.
check - checking the empty cells or same digits neaby.
shift - deplace everything to the left and if it can be found sum same digits.
make_step - regulating of def shifh in right direction.
