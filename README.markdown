## Inside Job

### A Minecraft Inventory Editor for Mac OS X

![Inside Job Screenshot](http://mcspider.oc.tc/files/Inside%20Job.png)

Inside Job was written in early October 2010 by [Adam Preble](http://adampreble.net).

Features include:

- Native Cocoa interface.
- Drag and drop inventory editing with item images.
- Item list searchable by name or item number.
- Experimental "time of day" editing.

### System Requirements

Mac OS X 10.6 Snow Leopard or higher.

### Instructions

Inside Job operates on Minecraft's level.dat files, located in _~/Library/Application Support/minecraft/saves/.  While Inside Job was written to interact with Minecraft's data as safely as possible, it's entirely possible that it will destroy it completely.  Please back up your Minecraft saves folder before using Inside Job.

Be sure to save and exit any open Minecraft worlds before running Inside Job.  Once run, Inside Job will display a list worlds in the default minecraft world folder. Choose one of these worlds or select "Open Other" to load that worlds inventory. Note that Inside Job can only edit existing worlds.

To alter your inventory, use the item list at right to find the item you desire, then drag it into an  inventory slot.  Rearrange items by dragging them to different slots.  To copy an item, including its quantity, hold the Option key when you start dragging.

Note that Inside Job works differently from the Minecraft inventory screen in that it does not "swap" items when dropping an item onto another.  Instead, it replaces the item completely.  If you drag an item into a slot already containing that item, the quantity will be increased accordingly, up to 64.

To alter the quantity or damage of a particular item, click on its inventory slot. Edit the values in the inspector window.

After changing your inventory you will need to save the currently open world using the World menu, or Command-S.  Once you have saved the world you can open it in Minecraft.  Note that if a world is opened in Minecraft while it is open in Inside Job, you will need to reload it using the World menu, or Command-R.  This is because Minecraft's file locking system gives write access to the last program to open it.

### Release Notes

#### 1.1.2 - November 26, 2011

- Filtering of items list by type (ex: ~weapon ~item ~block)
- Allow editing of enchantments.
- Added Minecraft 1.2 items.

#### 1.1.1 - November 26, 2011

- Added editing of XP level, heath and food level.
- Disabled debug logging of world file.

#### 1.1 - November 23, 2011

- Added Minecraft 1.0.0 Items
- Revamped UI and icon.
- Show items with damage value in the items selector. (Logs,Wool,Dye,etc)

#### 1.0.9 - September 24, 2011

- Added Minecraft 1.8 Items

#### 1.0.8 - June 30, 2011

- Added Minecraft 1.7 Items

#### 1.0.7 - May 5, 2011

- Fixed a bug when adding items to the inventory with Cmd N. (Add Item by ID)
- Added graphics for the different sapling varieties.
- Added the spiderweb (ID 30)

#### 1.0.6 - April 19, 2011

- Updated for Minecraft 1.5

#### 1.0.5 Beta - March 23, 2011

- Recently opened worlds now display in the world selector.
- Now supports negative item numbers.
- New experimental 'Copy World Seed', menu item.

#### 1.0.4 - March 16, 2011

- New UI, added a world selector.
- Added preset saving and loading
- New 'Add Item by ID', menu item.

#### 1.0.3 - March 13, 2011

- Cloned from [/preble/InsideJob](http://github.com/preble/InsideJob)
- Inside Job now supports worlds created in Minecraft Beta 1.3
- Fixed a bug in the search field preventing deletion of text.
- New UI

### Credits

Inside Job uses [Matt Gemmell](http://mattgemmell.com/)'s MAAttachedWindow and [Brandon Walkin](http://www.brandonwalkin.com/)'s BWSheetController.  Item graphics were originally created by Mojang Specifications and compiled by Trojam and the Minecraft community.

### License

Inside Job is made available under the [MIT License](http://www.opensource.org/licenses/mit-license.html).  Its source code can be found on GitHub: [http://github.com/preble/InsideJob]().

	Copyright (c) 2010 Adam Preble
	Parts Copyright (c) 2011 Ben K

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in
	all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
	THE SOFTWARE.
