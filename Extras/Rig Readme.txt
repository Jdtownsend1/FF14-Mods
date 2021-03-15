This is just a quick and dirty readme, Full Guide for this Rig is located at : 

https://docs.google.com/document/d/1NCASPmecZKfp-NVFTRukR9-O7ygRFiOdCwiIcDRNPlg

-- Setup --

 When Opening the rig, you will likely get a message about being unable to find the appropriate textures.  That's ok, just close the message, then press M to open the material editor.

In the editor, under 'Scene Materials' double click on '00 - Clothing'; this will highlight the clothing material in the editor.

From here, Double Click the Map node connected to the 'Diffuse Color' option, this will select it.

Then, on the right under 'Bitmap Parameters', where it says 'Bitmap: <Long File name>' Click the file name, this will open a file browser.  Select the Clothing Diffuse Map file in the /3DS References/ Folder.

Repeat this process for the Bump Map bitmap, and then for the '00 - Skin' material with the skin diffuse/bump bitmaps.

You should now properly have textures loaded in the scene.


-- Morphers --

This rig comes set up with Morpher modifiers on most of the major body, Clothing, and Piercing meshes.

Simply select a mesh, then the Morpher modifier, and adjust the slider values as you like to change between body types.

For Futa/Trap morphers; there is a Futa_Base and Trap_Base mesh under the Morph Targets/Futa Targets/.  These are the base mesh which has the morpher component.

Create a copy of the Futa/Trap base, and a copy of the Base Leg/Trap Leg.  Adjust the morphers on these copies as you like, the use the Rigging Combine script to combine them.


-- Featureless and WVRType Bodies --

This rig includes 2 alternate base bodies to use with the morphers; one is a Featureless body set, which is designed for use under clothing, the other is a WVRType body, which is the same as default,
  except that it uses weights and triangulation set to match that of the BBWVR body pack.  If you want your mesh to 100% match exactly with the default BBWVR setup, use this.


-- Animations --

This rig contains multiple animations for testing.  Simply slide the time slider along at the bottom to see them play out.

These are useful for testing if your gear may clip with the body in certain poses.

0->30 tests various bust sizes, with 20-30 being Cheat Engine/Trainer bust sizes.


-- Selection Groups & Skin Weight Files --

This rig includes selection groups for the bone sets for standard body/leg/hand/foot gear for your convience when setting up skin modifiers from scratch.

Add a Skin modifier -> Click the 'Add' Button to add bones -> Select a selection group at the top of the dialog as appropriate to the item you're working with.

After that you can load the weight files into the skin modifier under the advanced section of the modifier.

This is primarily useful in the event you accidentally destroyed your skin modifier, but can also be useful for loading in gear pieces without dragging in all their extra bone copies.


Example : 

Export a piece of gear from TexTools -> Open it in 3ds -> Save the skin weights to file for the gear & save the scene.

Open this rig -> [File->Import->Merge...] -> Select the scene you saved, and import only the gear piece, without influences.

Add a fresh Skin modifier to the gear piece -> Load in the bone selection set -> Load the skin weights from the file you saved.

You now have the gear properly set up in this rig, with animation support and no extra copies of bones/etc.

  Note: If the gear has unusual/non-standard bones such as Skirt bones, you will need to include those missing bones in the Merge dialog.


-- Feet & Hands --

This Rig includes TitanFirm feet, and default SE hands.

They can be set up with morphers though I did not include targets for hands, and only had one provisional morph target for the feet.

None-the-less, they are there for you to work with if you find that convenient, or you can just delete/hide/ignore them.