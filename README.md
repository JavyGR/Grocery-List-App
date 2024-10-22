# Grocery-List-App
 
This repository contains a simple web-based grocery list application built using Vue.js (via CDN) with custom styles and MDB (Material Design for Bootstrap) styling and components. The user can add items to a grocery list, mark them as "Picked Up" or "Pending," and delete them. Transitions are applied when items move between groups. The app is fully client-side and uses CDN links for all dependencies.

Features:
_Add grocery items with quantity to a list.
_Items can be marked as "Picked Up" or "Pending" using checkboxes.
_When an item is marked, it moves between the "Picked Up" and "Pending" groups.
_Transitions are applied when items move between groups.
_Each item can be deleted from the list.
_Responsive layout with MDB components and custom styles.

Technologies Used:
_Vue 3 (via CDN): A progressive JavaScript framework for building user interfaces.
_MDB (Material Design for Bootstrap) (via CDN): A popular UI kit for Bootstrap with Material Design components.
_FontAwesome (via CDN): Icon library used for providing user interface icons.

Project Setup:
No installation or build steps are required for this project. It runs directly in the browser with all dependencies loaded through CDNs.

CDN Links Used:
_Vue 3: https://unpkg.com/vue@3
_FontAwesome: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css
_MDB CSS: https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/7.3.2/mdb.min.css
_MDB JS: https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/7.3.2/mdb.umd.min.js

How to Use:
Clone or download the repository.
Open the html file in a web browser.
Enter the item name and quantity in the input fields.
Click "Add" to add it to the Pending group.
Mark the checkbox to move an item to "Picked Up" or back to "Pending".
Click the X icon to delete an item from the list.

Custom Styling
Some custom styles are included directly in the <style> tag within the html file to provide additional design adjustments.

Contributions
Feel free to submit issues or pull requests if you want to improve the project or add new features.