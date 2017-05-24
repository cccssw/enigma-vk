# enigma-vk
a fork of enigma

fork from this commit:
https://bitbucket.org/cuchaz/enigma/commits/6dfb5fc6325986b283fbdbbe7141ba8950811b46?at=default

origin project url:https://bitbucket.org/cuchaz/enigma/

added function:
 1. separate obfuscated classes, de-obfuscated classes,Inner/Anonymous Classes and None-Package Classes
 2. implemented default de-obfuscate function that mark words' length large than 5 as de-obfuscated tokens (named "markwords")
 3. add refresh action in the menu context
 4. add go next action so we can easily navigate back or next

#original description:
----
Enigma v0.10.4 beta
A tool for deobfuscation of Java bytecode

Copyright Jeff Martin, 2015


LICENSE

Enigma is distributed under the GNU Lesser General Public license version 3

Enigma includes a modified version of Procyon which is distributed under the Apache license version 2. Procyon is copyrighted by Mike Strobel, 2013

Enigma includes unmodified versions of the following libraries which are also released under the Apache license version 2.
	Guava
	Javassist
	JSyntaxPane

Copies of the GNU Lesser General Public license verion 3 and the Apache license v2 have been included in this distribution.


USING ENIGMA

Launch the GUI:
	java -jar enigma.jar
	
Use Enigma on the command line:
	java -cp enigma.jar cuchaz.enigma.CommandMain


OPEN SOURCE
https://bitbucket.org/cuchaz/enigma
----
