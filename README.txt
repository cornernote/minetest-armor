----------------------------------
Armor for Minetest
----------------------------------


Copyright (c) 2012 cornernote, Brett O'Donnell <cornernote@gmail.com>

Source Code: https://github.com/cornernote/minetest-armor
License: GPLv3

Textures by: Jordan Snelling (Jordach)
Texture License: GPLv3


----------------------------------
Description
----------------------------------


Allows players to craft and attach armor to their inventory to increase player strength.



----------------------------------
Crafts
----------------------------------

M = Material: Wood, Steel, Mese

Helmet:
MMM
M-M
M-M

Chestplate:
MMM
MMM
-M-

Boots:
M-M
M-M
M-M

Shield:
MMM
M-M
MMM



----------------------------------
Modders Guide
----------------------------------


To turn your craftitem into armor simply add one of the following to the groups in the node definition.
armor_helmet=X
armor_chest=X
armor_boots=X
armor_shield=X

X is from 1 to 4, where 1 is the highest grade armor (mese)

EG:
minetest.register_tool("your_mod:your_armor", {
	description = "Your Armor",
	groups = {armor_helmet=2},
})



----------------------------------
License
----------------------------------

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.



----------------------------------
Credits
----------------------------------

Thank you to the minetest community who has shared their code and knowledge with me.

