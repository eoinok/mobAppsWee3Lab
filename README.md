# Mobile Apps Week 3 Lab
The goals of this weeks lab are to:
  - Add Images to our app
  - Add a Component and Import it from another file
  - Add multiple inputs and style them appropriately
  - Add a button
  - Make the button respond when pressed

# Step 1 - Adding an Image
Create a new Snack on expo.dev. Go online and search for TUDublin Logo. Find the one you like best and save it in your downloads as TUDublinLogo.png or TUDublinLogo.jpg. Make sure it's a png or jpg file if you find a logo that isn't png or jpg keep looking. Go back to expo.dev. Beside the Project folder on the left in the files section, click on the three dots to expand the Menu underneath and select the "Import files" option. Import the file png or jpg file and make sure it gets moved or saved into the assets folder.
To add in this logo to our snack we are going to create it as a separate component. To do this, Underneath the Project folder, right click on the "components" folder and select the "New file" option. Call the file Logo.js. Add the following code into your new Logo.js file.

```
import {Image} from 'react-native';

export default function Logo() {
  return (   
    <Image source={require('../assets/tudublin.png')}/>
  )
}
```
To use this componenet in your app. Add the <Logo/> inside the <View> </View> tags inside your App.js component.

# Step 2 

