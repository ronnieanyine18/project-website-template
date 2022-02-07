MobileApartment 
Site: https://ronnieanyine18.github.io

# Introduction 

This is an internet based application which is aimed at easing the communication between tenants, landlords and Caretakers in regards to service delivery

From version 3.0, the menu bar at the top is moved into a single file (menu.html) for better management. Each template page will now use jQuery to load the menu bar file (menu.js), as shown below:
```html
<script src="js/menu.js"></script>
```
If your website is static and requires no user interactions, I recommend copying the code from the menu file (menu.html) into the menu-container div in your html template.
```html
<div class="menu-container">
  [copy everything in the menu.html and paste the code here]
</div>
```
In this way, you can remove the script line that loads jQuery in the header of the html and also delete the files for loading the menu bar (menu.html and menu.js).

This template is tested and worked on:
- macOS Mojave
  - Chrome 77
  - Safari 12
  - Firefox 68
- Windows 10
  - Chrome 77
  - Firefox 68
  - Edge 44
- Android 7, 8, 9, and 10
  - Chrome 77
  - Firefox 68
- iOS 12 and 13
  - Chrome 77
  - Safari
  - Firefox 18

# Problems and Bugs
Here are the problems and bugs that I plan to address in the future. If you fixed them, please do not hesitate to send me a pull request, and I would be very grateful. Please also report problems and bugs in [GitHub Issues](https://github.com/yenchiah/project-website-template/issues).

- On mobile Safari, the menu on the top will not close after opening it. This is because the menu icon on mobile Safari retains focus after a touch event, and the menu relies on the loss of focus event of the icon to close.

# Way Forward

- Extend the application to manage a number of buildimgs in different locations 
- Engage the Technicians in the direct service request replies 
- 

# Remarks and Appreciation 
I welcome and appreciate contributions taken byn the whole team right awy from the planning, codes building, fixing of the bugs, system testing and then implementation of the application. We intend and look forward to more easing of the apartment management fratenity as we come up with more vibrants and user friendly features 
