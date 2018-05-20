Show a list of users having birthday in block & seperate page.



Steps to do before installing a module
  Download & install date contrib module (If not enabled)
  visit admin/config/people/accounts/fields to create new field for dob. provide machine name as dob for DOB field.
  create new account field for user's first name as first_name.
  Assign date pop-up calender as widget type for DOB field.
  Create new image style (70px-square) for user's picture style. Add Scale and crop effect with 70 px Width and 70 px Height for better display. If you need to display other image style for user picture, you can change it in user's account settings form. (admin/config/people/accounts)
  Also add default profile picture in user's account settings form. As we are using image style to show user picture, add these image in "files" directory.(admin/config/people/accounts)
Download the module and install like other modules in drupal.
