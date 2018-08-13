# 0. Unity User Manual (2018.1)

# 1. Working in Unity
## 1.1. Basics
### 1.1.1. Downloading and installing Unity
#### 1.1.1.1. Deploying Unity offline
### 1.1.2. 2D or 3D projects
### 1.1.3. Project Templates
### 1.1.4. Getting started
#### 1.1.4.1. The Learn tab
### 1.1.5. Learning the interface
## 1.2. Asset Workflow
  * import: 3D modle/audio file/an image/files unity supports
  * create: Animator Controller/Audio Mixer/a Render Texture
### 1.2.1. Common types of Assets
  * Image files/FBX and model files/meshes and animations/audio files/other assert types/standard assets
### 1.2.2. Primitive and placeholder objects
  * Cube/Sphere/Capsule/Cylinder/Plane/Quad
### 1.2.3. Asset packages  
  * Asset packages: Asset Store
  * Unity packages: Package Manager Window
  * Importing Packages: Customer Package/Standard Asset
  * Exporting Packages:
  * Updating Packages
  * Upgrading Standard Assets: Standard Assets do not upgrade automatically when you upgrade the editor
## 1.2.4. Using the Asset Store
  * Window->Asset Store
  * Location of download Asset files:
    * Windows: C:\Users\accountName\AppData\Roaming\Unity\Asset Store
    * MacOS: ~/Library/Unity/Asset Store
## 1.3. The Main Windows
### 1.3.1. The Project Window
  * Favorite/Searching(Type:ORed together/Label:ORed together)
  * Shortcuts: the following keyborad shortcuts are available when the browser view has focus.
  
  shortcut|meaning
  --------|-------
  F|Frame selected (ie. show the selected asset in its containing folder)
  Tab|Shift focus between first column and second column (two columns)
  Ctrl/Cmd+F|Focus search field
  Ctrl/Cmd+A|Select all visible items in list
  Ctrl/Cmd+D|Duplicate selected assets
  Delete|Delete with dialog
  Delete+Shift|Delete without dialog
  Backspace+Cmd|Delete without dialog (OSX)
  Enter|Begin rename selected (OSX)
  Cmd+down arrow|Open selected assets (OSX)
  Cmd+up arrow|Jump to parent folder (OSX, Two columns)
  F2|Begin rename selected (Win)
  Enter|Open selected assets (Win)
  Backspace|Jump to parent folder (Win, Two columns)
  Right arrow|Expand selected item (tree views and search results). If the item is already expanded, this will selected its first child item  
  Left arrow|Collapse selected item (tree views and search results). If the item is already collapsed, this will select its parent item
  Alt+right arrow|Expand item when showing assets as previews
  Alt+left arrow|Collapse item when showing assets as previews
### 1.3.2. The Scene View  
  * Showing Game Objects
#### 1.3.2.1. Scene View navigation
  * Scene Gizmo: Mac trackpad gestures
  * Moving/Orbiting/Zooming: [Shift+]arrow key/Hand tool(Alt/Right click/Left click)/Flythrough mode
  * Movement shortcuts
#### 1.3.2.2. Positioning GameObjects  
  * To select or deselect multiple GameObjects, hold the Shift key while clicking, or drag a rectangle around multiple GameObjects to select them
  * Highlight color change: Unity->Preference->Color->Selected Wireframe->Selected Outline
  * Move/Rotate/Scale/RectTransform
  * Gizmo handle position toggles
#### 1.3.2.3. Scene View Control Bar  
  * Draw mode menu: Shaing mode/Miscellaneous/Deferred/Global Illumination/Material Validator
  * 2D, Lighting, Audio switches
  * Effects button and menu
  * Gizmo menu
  * Search bo
#### 1.3.2.4. Gizmo menu
  * 3D Icons/Show Grid/Selection Outline/Selection Wire/Built-in Components
  * Gizmos and Icons: Camera/Light direction Gizmo
  * Show Grid
  * Selection Outline and Selection Wire
  * Build-in Components
### 1.3.3. The Game View  
  * Play mode
  * Game view Control Bar
  * Gizmo menu
  * Advanced options
### 1.3.4. The Hierarchy window  
  * Parenting
  * Making a child object
  * Alphanumeric sorting
  * Multi-scene editing
### 1.3.5. The Inspector window
  * display details information about currently selected GameObject
  * inspecting GameObjects
  * inspecting Script Variables
  * inspecting Assets
  * prefabs[template like]/project setting/icons and labels/reordering components
#### 1.3.5.1. Assigning icons
  * image-only icon/label icon
#### 1.3.5.2. Editing Properties
  * others/colors/gradients/curves/arrays
  * Editing Several Objects at once
#### 1.3.5.3. Swatch libraries
  * save and choose
#### 1.3.5.4. Inspector Options
  * lock
  * debug/normal mode
### 1.3.6. The Toolbar
### 1.3.7. Searching
  * project view/scene view
### 1.3.8. Other windows
  * console window/animation window/profiler window
  * lighting window/occlusion culling window
### 1.3.9. Customize workspace
### 1.3.10. Unity Hotkeys
  * [HotKeys](https://docs.unity3d.com/Manual/UnityHotkeys.html)
## 1.4. Creating HamePlay
## 1.5. Editor Features
## 1.6. Advanced Development
## 1.7. Advanced Editor Topics
## 1.8. Licenses and Activation
## 1.9. Upgrade Guides

# 2. Importing
## 2.1. Model importing workflows
### 2.1.1. Importing humanoid animations
  * Define the Rig type and create the Avatar
  * Correct or verify the avatar's mapping
  * Once you are finished with the bone mapping, you can optionally click the Muscles & Settings tab to tweak the Avatar's muscle configuration
  * You can optionally save the mapping of your skeleton's bones to the Avatar as a Human Template (.ht) file
  * You can optionally limit the animation that gets imposed on certain bones by defining an Avatar Mask
  * From the animation tab, enable the import animation option and then set the other Asset-specific properties
  * If the file consists of multiple animations or actions, you can define specific action ranges as Animation Clips
  * For each Animation Clip defined in the file, you can ...
  * To save your changes, click the apply button at the bottom of the Import settings window or Revert to discard your changes
  
  * Creating an Avatar Mask/import time or runtime/Avatar Mask Asset
### 2.1.2. Importing non-humanoid animations
  * Non-humanoid skeletons could have a huge range of possible bone structures
  * The solution to dealing with this complexity is that Unity only needs to know which bone is the Root node.
  * The generic avatar is not the same as the humanoid avatar, but it does appear in the project view, and it hold the root node mapping.
## 2.2. Model Import Settings window
  * To view the import settings in the Inspector, click on the file in the Project window. You can customize how Unity imports the selected file by setting the properties on four tabs on this window.
### 2.2.1. Model tab
### 2.2.2. Rig tab
  * By default, when you select a model in the Project view, Unity determines which Animation Type best macthes the selected Model and displays it in the Rig tab.
#### 2.2.2.1. Avatar mapping tab
  * Saving and Reusing avatar data (Human template files)
#### 2.2.2.2. Avatar muscle & Setting tab
#### 2.2.2.3. Avatar mask window
#### 2.2.2.4. Human Template window
### 2.2.3. Animation tab
  * 略 (TODO)

# 2D
  # this section contains documentation for users developing 2D games in Unity.
  
  
  
  
  
  
  
  
  
  
  
  
