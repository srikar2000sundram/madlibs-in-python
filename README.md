# madlibs-in-python

#youtuber = "Srikar Sundram" #going to be some string

#String concatination can be done via various methods
#a few ways are shown below
#print("subscribe to " + youtuber)
#print("subscribe to {}".format(youtuber))
#print(f"subscribe to {youtuber}") #Cleanest way

adj = input("Adjective :")
verb1 = input("Verb : ")
verb2 = input("Verb2 : ")
infectious_person = input("infectious person :  ")

madlib = (f" Life is so clumsy & {adj}! , But we have to deal with it at any cost. \
I love to {verb1} , it makes my {verb2} always. \
It also makes you an {infectious_person}")
print(madlib)
