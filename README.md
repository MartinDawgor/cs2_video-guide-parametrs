# cs2_video-guide-parametrs

A detailed description of the commands from cs2_video.txt, the graphics configuration file.  
by MartinDawgor (@Lermor1), Chat: t.me/CataloguePCS.

- The list contains a selection of all commands used by the game engine.  
Some of them are changed directly within the game settings, while others are hidden and called separately.  
In total, there are approximately 113 references to graphics parameters within the game files.  
Experimentally, by replacing the config, we were able to determine which parameters the game accepts and which it discards.

- Below is a list of 72 commands from a sample, with detailed explanations in the configuration file.  
Descriptions were taken from open documentation and discussion forums.  
The list is divided into standard commands and others found in the code and accepted by the engine during initialization.  
The range of accepted values ​​is indicated in parentheses. Some require a read-only flag to be fixed.

- The structure of the final file should be preserved as in the original file.  
The order and placement of commands does not affect the operation of the configuration file.  
Extra lines with comments or empty values ​​can break the configuration file.  
It is important to preserve tabs: from the beginning of the line to the first quotation mark of the parameter name,  
there is one tab, and between the parameter and the value, there are two tabs.  
A sample file with the correct structure is at the very bottom.

- To prevent CS2 from overwriting files, you need to check the "Read-only mode" box in the file's properties. Otherwise, the game may overwrite them.  
When this box is checked, changing the parameters through the settings within CS2 is not possible, and is not recommended.  
It is important to change the values ​​within the config file, and then set the file to read-only.
