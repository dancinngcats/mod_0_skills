Class: Menu
Instance: Brunch Menu at Denver Biscuit Company

Attributes:
* heading (string) = "Denver Biscuit Company - Brunch Menu"
* number_of_items (integer) = 12
* section (array) = ["appetizers", "highlights", "desserts", "drinks", "kids menu"]
* last_updade (datetime) = 8/20/2020
* images (boolean) = false

Methods:
* add_new_item (changes the value of number_of_items and the last_update):
    * number_of_items = 13
    * last_update = 11/1/2020
* add_photos (reassigns the value of images): images = true
* remove_kids_menu (changes value of the attribute number_of_items, changes value of the last_update, and removes one item from the array section):
    * number_of_items = 10
    * last_update = 11/2/2020
    * ["appetizers", "highlights", "desserts", "drinks"]
* change_heading (changes the value of heading): heading = "Our Fall Brunch Menu"
* remove_typos (changes the value of the last_update): last_update = 11/3/2020
