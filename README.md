The app uses the Scaffold widget as the root widget.
The app has a custom AppBar with the title "Photo Gallery".
The body of the app is wrapped in a SingleChildScrollView to enable scrolling.
Inside the SingleChildScrollView, a Column widget is used to organize the app's content.
A Container is displayed with a welcome message: "Welcome to My Photo Gallery!".
Below the welcome message, a TextField is added for users to search for specific photos.
A Wrap widget is used to display a grid of photos. The photos are network images and are represented by ElevatedButton widgets.
Each photo button includes an image and a caption below it. Clicking on a photo button shows a Snackbar with the message "Clicked on photo!".
Below the photo grid, a ListView.builder is used to display a list of ListTile widgets.
Each ListTile represents a photo with a title and a subtitle. The ListTile includes a network image as the leading widget.
An IconButton is added as the floatingActionButton. When pressed, it displays a Snackbar with the message "Photos Uploaded Successfully!".
Overall, this code creates a basic photo gallery app with a responsive layout, search functionality (UI only), and interactive features like clicking on photos and displaying Snackbars.![image](https://github.com/Rokeya0/module.ass6/assets/135530632/7366fd5a-f74f-497a-bed3-6cfcc7c005ec)
