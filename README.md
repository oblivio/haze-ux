# haze
Zero knowledge.

haze 1.0.5 Genesis - 

https://web.hazedaily.com


Haze is a end-to-end encrypted communication platform using 256 bit AES encryption built on top of the oblivious system.
More information on the oblivious system could be found at

http://www.github.com/oblivio/oblivious 

While the purpose of Haze is end-to-end encrypted communication (client-to-client encryption) - oblivious takes care of the back-end process. The oblivious system itself is built in a very simple, easy to understand way. When you create a new entry, all you are doing is creating a file (following a particular folder/naming structure); The contents of the file will be the contents of your entry (but encrypted with a server key); This entry can have certain attributes like expiration time, burnafterreading, and open-discussions(comments). If you are the creator of an entry, you will get a special 'delete token' that let's you remove the entry before its expiration date. 

=== Encryption ===

	The simplest way to think of encryption is to think of password protection. When you use a password to protect a piece of information, you are using a form of encryption. Without the password, the data is worthless.


=== End-to-End Encryption? ===

	When you create a haze entry, the content of your haze entry gets encrypted using AES 256 bit encryption on the client-side before the data is sent to the server. The server contains only encrypted information, and is oblivious as to what the actual content is. The server then returns an haze id to the client. A typical haze id will look something like this: <span style="display: inline-block;word-break: break-all;">0adedd281fdbc2f8</span>. The client can use this haze id to access the encrypted information in the haze entry. The 256 bit key never touches the server - it only exists on the client. 


	The 256 bit key is the 'password' to your haze entry. Without this, the data in your haze entry is not usable. A typical key would look something like this: 	+BnEcW9gAP7bz3I/1LDi5UMygbt14GXNTWxgX+9GCMw=
	
=== Blackbook? === 
	
	The Blackbook let's you keep track of your haze entries by storing keys, aliases, and other entry data using HTML5 localStorage. 
	
=== How do I start an encrypted conversation? === 
	
	To start a conversation, click on the 'Add' button.
	
	At this point, you will be able to configure options for your haze entry such as expiration time, message, image, category, password-protection or custom meta-data.  
	
	Once your entry is configured, you can proceed to create it. Once the entry has been created, it will be loaded onto your Blackbook. From your Blackbook, you will be able to generate a password-protected invite for your haze entry.  
	
	From your Blackbook, you can also view or alias an entry. To alias an entry, simply click on the 'Alias' button and enter the required information. To view an entry, click on 'View' and the entry contents will become available. While viewing a haze entry, you also have the option to add comments containing text/image.
	
=== An Invite? ===

	A haze invite is an image containing an invite code hidden in the pixel information. When this invite code is processed by the invite recipient, he will be able to access the entry for which the invite was generated.


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
