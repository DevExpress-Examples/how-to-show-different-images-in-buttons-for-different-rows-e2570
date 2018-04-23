# How to show different images in buttons for different rows


<p>Usually, different editors should be provided via the  <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsGridGridView_CustomRowCellEditForEditingtopic">GridView.CustomRowCellEditForEditing</a>  event. (For more information, please see the  <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument747">Assigning Editors to Individual Cells</a>  help topic.)</p><p>However, when you need to show many various icons in buttons for inplace ButtonEdits, this approach is not the best solution, because you need to implement a custom caching mechanism to prevent creating duplicate RepositoryItems. </p><p>This example demonstrates how to create a helper class which provides images for cells dynamically, via an event. In this case, you do not need to create additional RepositoryItems. You just need to copy required units to your project and create an instance of the DifferentButtonIconsHelper class.</p>

<br/>


