# haze
Zero knowledge.

haze 1.0.3 Genesis - 

https://web.hazedaily.com


Haze is a end-to-end encrypted communication platform using 256 bit AES encryption built on top of the oblivious system.
More information on the oblivious system could be found at

http://www.github.com/oblivio/oblivious 

The haze front-end is very simple and straight forward. There are four main navigation buttons which I'll describe below.

1.) Public Feed - 
The public feed displays haze entries for a particular category. Upon selecting a category, the available entries will be displayed. From this screen you can either 'View' an entry, or 'Alias' it. 

2.) Blackbook -
Similar to the public feed, but keeps track of your personal haze entries. You will be able to generate 'invites' only for entries available in your Blackbook.

3.) Add Entry -
The add entry button lets you add an entry to your Blackbook. You can do this by selecting the 'Existing Entry' option and processing an invite, or by selecting the 'New Entry' option and creating a new haze entry.

4.) Settings -
From here you will be able to manage your Blackbook settings. 


While the purpose of Haze is end-to-end encrypted communication (client-to-client encryption) - oblivious takes care of the back-end process. The oblivious system itself is built in a very simple, easy to understand way. When you create a new entry, all you are doing is creating a file (following a particular folder/naming structure); The contents of the file will be the contents of your entry (but encrypted with a server key); This entry can have certain attributes like expiration time, burnafterreading, and open-discussions(comments). If you are the creator of an entry, you will get a special 'delete token' that let's you remove the entry before its expiration date. 


=== ORIGINS ===

Both haze and oblivious have their origins in ZeroBin - a minimalist, opensource online pastebin where the server 
has zero knowledge of pasted data. 

More information on the project page:

http://sebsauvage.net/wiki/doku.php?id=php:zerobin


------------------------------------------------------------------------------
------------------------------------------------------------------------------

Copyright (c) 2015 Fabian Valle (www.fabian-valle.com)

This software is provided 'as-is', without any express or implied warranty.
In no event will the authors be held liable for any damages arising from 
the use of this software.

Permission is granted to anyone to use this software for any purpose, 
including commercial applications, and to alter it and redistribute it 
freely, subject to the following restrictions:

    1. The origin of this software must not be misrepresented; you must 
       not claim that you wrote the original software. If you use this 
       software in a product, an acknowledgment in the product documentation
       would be appreciated but is not required.

    2. Altered source versions must be plainly marked as such, and must 
       not be misrepresented as being the original software.

    3. This notice may not be removed or altered from any source distribution.

------------------------------------------------------------------------------
------------------------------------------------------------------------------

Copyright (c) 2012 Sébastien SAUVAGE (sebsauvage.net)

This software is provided 'as-is', without any express or implied warranty.
In no event will the authors be held liable for any damages arising from 
the use of this software.

Permission is granted to anyone to use this software for any purpose, 
including commercial applications, and to alter it and redistribute it 
freely, subject to the following restrictions:

    1. The origin of this software must not be misrepresented; you must 
       not claim that you wrote the original software. If you use this 
       software in a product, an acknowledgment in the product documentation
       would be appreciated but is not required.

    2. Altered source versions must be plainly marked as such, and must 
       not be misrepresented as being the original software.

    3. This notice may not be removed or altered from any source distribution.

------------------------------------------------------------------------------
------------------------------------------------------------------------------

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

-------------------------------------------------------------------------------
