# Add group page description 

## name 
 
represen name of the group 

## Object permissions 

this is a list of checklists that gives this group some managerial permissions , the group have the checked box permissions 

  1- Event Category 

  2- Site : this option is related to sites section in the settings (eg: adding subdomains (add) , changing domain name and details (change) delete unwanted subdomains(delete))

  3- Task : this option is related to task section in the settings , the task is a task given to spesific user to do a specific feature (add task , change existed tasks , delet task)

  4- Color setting : this option is related to Color section in the settings , change means that this group have the ability to change the footer and navbar colors (to see description of this feature go to [change_theme](./change_theme.md)) 

  5- Workflow : this option is related to workflow section in the settings ,add workflow ,change existing workflow, delete workflow (to see description of this feature go to []())

  6- Locale : this option is related to workflow section in the settings (to see description of this feature go to []())

  7- Simple translation

  8- Footer setting : this option is related to Footer section in the settings this allows the group to change the content of the footer (to see description of this feature go to [adding_footer](./adding_footer.md))

  9- Menu : this option is related to Menu section in the settings this allows the group to change the content of the Menu (to see description of this feature go to [adding_navbar](./adding_navbar.md))

  10- Redirect : this option is related to Redirect section in the settings tis allows the group to add , change or delete redirects (to see description of this feature go to []())

  11- Group : this option is related to Group section in the settings this allows the group to add , change or delete groups in the website (to see description of this feature go to [user_managment](./user_managment.md))

  12 - User : this option is related to User section in the settings this allows the group to add , change or delete users in the website (to see description of this feature go to [user_managment](./user_managment.md))

## Other permissions 

always check the box Can access Wagtail admin to allow your group to enter the admin side of the website 

## Page Permissions

this permission is for pages editing , means that the added pages are available for this group

  - first you should click on ADD A PAGE PERMISSION , this will add an empty page to the group 

  - click on choose a page 

  - select the page that you want this group to acsses 

  - check the boxes that you want your group to go with the available page (add child pages , edit currrent content of the pages , puplish the changes page , bulk delete of pages , loc or unlock the page)

note : you can add more than one page to the same group repeting the same steps 

## Document Permission 

this allows the group to access the documents section that you can see in your side nav 

the group can add edit or choose from documents depend on the permission checklist (too know more about this feature see ()[])


## Image Permission 

this allows the group to access the Images section that you can see in your side nav (too know more about this feature see ()[])

- select the collection that you want this group to access 
- the group can add edit or choose from images depend on the permission checklist 

## collection managment permission 

this allows the group to manage collections  (too know more about this feature see ()[])

- first you should choose the collection you want your group to access

- Add - grants the ability to create new collections underneath this collection.

- Edit - grants the ability to edit the name of the collection, change its location in the collection tree, and to change the privacy settings for documents within this collection.

- Delete - grants the ability to delete collections that were added below this collection.

Note: a collection must have no subcollections under it and the collection itself must be empty before it can be deleted.

the collection managment part cited from [@https://docs.wagtail.org/en/latest/editor_manual/administrator_tasks/managing_workflows.html]