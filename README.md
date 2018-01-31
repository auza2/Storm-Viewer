# Storm-Viewer
<img src="https://media.giphy.com/media/3o6nV4eEH1c7oPvY0o/giphy.gif" width="244" height="480" />

# Description
In this project I read in multiple jpg files from a directory using a FileManager and showed their file names in a UITableViewController. When a cell is selected a detailed view showing the whole image is pushed onto the the navigation controller and therefore is showed on the screen. Since the table view controller is embedded in a navigation controller, we are given a back button on the navigation bar. This bar was slightly tweaked to disappear/reappear on tap as to see the whole image which was created using UIImage. Since all images are not the same and the size of the screen can vary, we created a constraint on the UIImage called 'Aspect Ratio' which means that the image will keep the ratio of its original image no matter what. This, along with a constraint holding the edges of the image to the edges of the screen, results in what you see in the gif above when the orientation is changed. The constraint anchoring the edges of the UIImage to the edge of the screen was done with AutoLayout's Resolve Layout Issue Feature

*Project 1 of the Hacking with Swift*
