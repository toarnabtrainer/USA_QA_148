Pressman E-Book Download Link:
https://www.mlsu.ac.in/econtents/16_EBOOK-7th_ed_software_engineering_a_practitioners_approach_by_roger_s._pressman_.pdf

Python Download Link:
Anaconda Download Link: https://www.anaconda.com/products/distribution

Online Python Editors:
https://onecompiler.com/
https://www.onlinegdb.com/

Python Study Material Links:
Python for you and me: https://pymbook.readthedocs.io/en/latest/
Python Practice Book: https://anandology.com/python-practice-book/index.html
Learn Python Programming (programmiz.com): https://www.programiz.com/python-programming
Learn Python Programming (data-flair): https://data-flair.training/blogs/python-tutorial/


Online Editor Link: https://www.onlinegdb.com/

# Performing addition of two user given numbers
num1 = int(input("Please enter the first number: "))
num2 = int(input("Please enter the second number: "))
total = num1 + num2

print ("So the sum of", num1, "+", num2, "=", total)
print ("So the sum of " + str(num1) + " + " + str(num2) + " = " + str(total))
print ("So the sum of {} + {} = {}".format(num1, num2, total))   # {} is called place holder
print ("So the sum of {0} + {1} = {2}".format(num1, num2, total))   # using indexed place holder
print ("So the sum of {2} + {1} = {0}".format(total, num2, num1))   # using indexed place holder
print ("So the sum of {fnum} + {snum} = {tot}".format(fnum = num1, snum = num2, tot = total))   # using labeled place holder

