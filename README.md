# LEARN_PYTHON
Basics for python
#study of printing anf f - format 
first_name = 'prasanna'
last_name = 'balaji'
full_name = f"{first_name} {last_name}"
message = f"I AM VERY HAPPY MR. {full_name.upper()} FOR YOUR PRESENCE"
print(message)

print("\tpython")  #to add a tab : \t
print("prasanna\nbalaji\nbalamurugan") #to make values appear in next line

#strips are used to void white spacing in the values for a neat output which is usefull for readers
cat = " meow "
print(cat.rstrip())
print(cat.lstrip())
print(cat.strip())

#removing prefix and suffix
url = 'http://python.org'
#removing prefix
print(url.removeprefix('http://')) 
#remove sufix
print(url.removesuffix('python.org'))

