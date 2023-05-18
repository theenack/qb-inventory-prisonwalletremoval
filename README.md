# qb-inventory-prisonwalletremoval


So in qb-core/config.lua edit the max slots from 41 to 40
QBConfig.Player.MaxInvSlots = 41 -- Max inventory slots for a player

QBConfig.Player.MaxInvSlots = 40 -- Max inventory slots for a player

Also in lj-iventory/config.lua change the max slots from 41 to 40
MaxInventorySlots = 41

MaxInventorySlots = 40

Also in lj-iventory/html/js/app.js comment out line 2890 to 2892
var elem =
                '<div class="z-hotbar-item-slot" data-zhotbarslot="41"> <div class="z-hotbar-item-slot-key"><p>6 <i style="top: -62px; left: 58px;" class="fas fa-lock"></i></p></div><div class="z-hotbar-item-slot-img"></div><div class="z-hotbar-item-slot-label"><p>&nbsp;</p></div></div>';
            $(".z-hotbar-inventory").append(elem);

//var elem =
                //'<div class="z-hotbar-item-slot" data-zhotbarslot="41"> <div class="z-hotbar-item-slot-key"><p>6 <i style="top: -62px; left: 58px;" class="fas fa-lock"></i></p></div><div class="z-hotbar-item-slot-img"></div><div class="z-hotbar-item-slot-label"><p>&nbsp;</p></div></div>';
            //$(".z-hotbar-inventory").append(elem);
