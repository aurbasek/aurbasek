from life_support_items import coffee
from time import sleep

while True:
    if coffee.is_empty:
        print("Emergency! Coffee levels critical! Refilling...")
        coffee.refill()
    else:
        print("All systems normal. Enjoying sweet nectar of life...")
    sleep(10)  # because sometimes life makes you wait...
    coffee.sip()
    

<!---
aurbasek/aurbasek is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
