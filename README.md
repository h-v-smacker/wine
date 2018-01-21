Wine mod for Minetest

by TenPlus1

Depends: Farming Redo

This mod adds a barrel used to ferment grapes into glasses of wine, 9 of which can then be crafted into a bottle of wine. It can also ferment honey into mead, barley into beer, wheat into weizen (wheat beer), and apples into cider.

Change log:

- 0.1 - Initial release
- 0.2 - Added protection checks to barrel
- 0.3 - New barrel model from cottages mod (thanks Napiophelios), also wine glass can be placed
- 0.4 - Added ability to ferment barley from farming redo into beer and also honey from mobs redo into honey mead
- 0.5 - Added apple cider
- 0.6 - Added API so drinks can easily be added, also added wheat beer thanks to h-v-smacker and support for pipeworks/tubelib

Lucky Blocks: 8


Wine Mod API
------------

wine:add_item(list)

e.g.

wine:add_item({
	{"farming:barley", "wine:glass_beer"},
	{"default:apple", "wine:glass_cider"},
})
