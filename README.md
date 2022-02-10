# TTV-Custom
# custom emotes for wow TTV addons

# In order for this to work you must edit the LUA files within the TTV addon.

# To create an image:
#    Find a piece of media that you enjoy. 
#    Edit the image to either a jpg, png, jpeg, or some file type that can be converted easily on a web converter (such as zamzar)
#    Convert the image into a TGA file and name it the code word you'd like to type in game for it to appear.
#    Paste the file into the following folder 
#       Computer > Local Disk > Program Files > World of Warcraft > Classic > Interface > Addons > Twitch Emotes > Emotes > TwitchTV > "file goes here"

# To edit the Lua File:
#    Go to the addon folder within TTV.
#    Computer > Local Disk > Program Files > World of Warcraft > Classic > Interface > Addons > Twitch Emotes > Emotes.lua
#    
#    In this file go to the "TwitchTV" secion, There are 2 section titles. You need to copy the following into both while matching the surrounding code closely. 
#     
#     ["Filename"] = "Interface\\AddOns\\TwitchEmotes\\Emotes\\TwitchTV\\Filename.tga:??:??",
#     
#     and 
#
#     ["Filename"] = "Filename",
#
#     Replace 'Filename' with the name of the TGA file image you want places,
#       and replace the '??:??' with the pixel dimensions of your tga image. (usually 28:28 or 64:64)

# Once this is done your emotes will appear for you and anyone else who has made this change. If you update you will have to re-make the changes. Have fun :)
