# pilotWork

pilot = """This is a test. 
Word. 
Word. 
More contnet."""

sub_pilot = "Nothing"

print("\n")
print("This is Original text")
print(pilot)
print("\n")

print("Word count is =",pilot.count("Word"))
print("Below example is text changed")
print(pilot.replace("contnet", "content"))

print("\n")
def check(pilot, sub_pilot):
     if (pilot.find(sub_pilot) == 1):
          print(pilot.replace("Nothing", "Something"))
     else:
      	  print("'Nothing' word is not found")
check(pilot, sub_pilot)
