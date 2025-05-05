# UMGViewer
A unreal engine plugin.

Edit UMG when PIE just like in the UMG editor.

### How To Use:

#### Open the tool windows from Toolbar-Window-UMG Viewer.
<img src="https://github.com/user-attachments/assets/960ab51f-7cc2-448d-bfaf-55d53d3866d2" width="30%">

#### Then you can see the tool window.
<img src="https://github.com/user-attachments/assets/fd825e6b-f905-4643-9e8b-f1c3b6024f7c" width="50%">

#### Every widget add to viewport would display on the tree view.
Tree view left will automatically update when any widget added or remove to viewport. 

For dynamic added widgets, click "Refresh" button on tool bar to update tree view.

### Here is my example：
<img src="https://github.com/user-attachments/assets/3da1cd38-5934-4843-be88-a00f3a357fa7" width="50%">

#### Select widget item on tree view left, and edit its style or property on the detail view right. 
You can easily edit their styles and properties on detail view when PIE. Such as text, color and more.
<img src="https://github.com/user-attachments/assets/20c938a3-3fe4-4a02-b444-d8b54b435e64" width="50%">

#### You can also click checkbox to toggle visibility for each widget item quickly.
<img src="https://github.com/user-attachments/assets/5e89576a-b5a2-45af-8acd-e98eac285e84" width="50%">

### Simulate Click
#### Select the widget, then click "Simulate Click" button on toolBar.
<img src="https://github.com/user-attachments/assets/f836eb82-cd4c-4f27-9577-16ffe75f75ae" width="50%">

For buttons, their onClick event would be triggered.

For other widgets, the onMouseButtonDown(LeftButton) and onMouseButtonUp(LeftButton) would be triggered.
