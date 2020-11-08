Class: Menu

Attributes:
* heading (string)
* number_of_items (integer)
* section (array)
* last_updade (datetime)
* images (boolean)

Methods:
* add_new_item (increments number_of_items by 1 and changes the value of  last_update)
* add_photos (reassigns the value of attribute images)
* remove_kids_menu (changes value of the attribute number_of_items, changes value of the last_update, and removes one item from the array section)
* change_heading (changes value of the heading)
