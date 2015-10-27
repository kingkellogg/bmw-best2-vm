# bmw-best2-vm
A Virtual Machine implementation capable of executing BMW's proprietary BEST2 instruction set.

#Intro

I wrote this in order to execute jobs that are located in BMW's *.prg files. These jobs are actually programs compiled in BMW's own proprietary instruction set, called BEST2, which is a word game for "BEschreibungssprache für STeuergeräte", or "description language for ECUs" in English. The goal of this project was to create an environment which could run these jobs, in order to be independant from BMW's own software tools, namely EDIABAS.

#So how does it work?

I'll soon commit a sample application which shows how to execute jobs. Please note that this VM is far from done, as very many features of the BEST2 language specification are still missing. It is uncertain if i'll ever finish it completly. Feel free to attempt for yourself.

#Can I use it in a project of mine?

Sure, if you want. Just do me a favor and attribute me somewhere. 

#Why Delphi?

Dunno. It was my favourite language back when I started this. Nowadays, i'd probably write it in C++ or something.
