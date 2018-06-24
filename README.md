# Zork

                    GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU General Public License is a free, copyleft license for
software and other kinds of works.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
the GNU General Public License is intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.  We, the Free Software Foundation, use the
GNU General Public License for most of our software; it applies also to
any other work released this way by its authors.  You can apply it to
your programs, too.

  When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
them if you wish), that you receive source code or can get it if you
want it, that you can change the software or use pieces of it in new
free programs, and that you know you can do these things.

  To protect your rights, we need to prevent others from denying you
these rights or asking you to surrender the rights.  Therefore, you have
certain responsibilities if you distribute copies of the software, or if
you modify it: responsibilities to respect the freedom of others.

  For example, if you distribute copies of such a program, whether
gratis or for a fee, you must pass on to the recipients the same
freedoms that you received.  You must make sure that they, too, receive
or can get the source code.  And you must show them these terms so they
know their rights.

  Developers that use the GNU GPL protect your rights with two steps:
(1) assert copyright on the software, and (2) offer you this License
giving you legal permission to copy, distribute and/or modify it.

  For the developers' and authors' protection, the GPL clearly explains
that there is no warranty for this free software.  For both users' and
authors' sake, the GPL requires that modified versions be marked as
changed, so that their problems will not be attributed erroneously to
authors of previous versions.

  Some devices are designed to deny users access to install or run
modified versions of the software inside them, although the manufacturer
can do so.  This is fundamentally incompatible with the aim of
protecting users' freedom to change the software.  The systematic
pattern of such abuse occurs in the area of products for individuals to
use, which is precisely where it is most unacceptable.  Therefore, we
have designed this version of the GPL to prohibit the practice for those
products.  If such problems arise substantially in other domains, we
stand ready to extend this provision to those domains in future versions
of the GPL, as needed to protect the freedom of users.

  Finally, every program is threatened constantly by software patents.
States should not allow patents to restrict development and use of
software on general-purpose computers, but in those that do, we wish to
avoid the special danger that patents applied to a free program could
make it effectively proprietary.  To prevent this, the GPL assures that
patents cannot be used to render the program non-free.

  The precise terms and conditions for copying, distribution and
modification follow.

                       TERMS AND CONDITIONS

  0. Definitions.

  "This License" refers to version 3 of the GNU General Public License.

  "Copyright" also means copyright-like laws that apply to other kinds of
works, such as semiconductor masks.

  "The Program" refers to any copyrightable work licensed under this
License.  Each licensee is addressed as "you".  "Licensees" and
"recipients" may be individuals or organizations.

***************************************************************************************
***************************************************************************************
***************************************************************************************

Autor:
Aniol Andrés Guiu

Zork:

He escrito los textos en inglés de modo que en esta explicación usaré los mismos nombres
Hay un total de 9 habitaciones:
Cell
Torture Chamber
Guards Room
Barracks
Kitchen
Servants Room
Treasure Room
Throne Room
Courtyard

y 8 zonas que son habitaciones simplificadas.

El objetivo es llegar a la courtyard y derrotar al Game Master, para hacerlo necesitas la llave que se consigue en el trono.

***********************************************************************************************************

Guía

Escribiendo Help se mostrará una lista de comandos.

Cell:
Aquí podemos coger "Note" y "Knife", los nombres de los objetos necesitan la mayúscula al principio para reconocerlos.
tanto para equipar el cuchillo como para leer la nota se usa el comando "Use Note" o "Use Knife". Si las armas no están equipadas no se sumarán sus stats.
Vamos al sur, 2 al este y otra vez al sur.

Torture Chamber:
Cogemos y equipamos el Buckler.
Norte, 2 al oeste y sur

Guards room:
Hay que luchar contra el goblin escribiendo repetidamente "attack"
Vamos al sur y luego al este

Barracks:
Cogemos y equipamos la Chainmail
Oeste y luego 2 al sur.

Servants Room:
Derrotamos al orco que nos dará un hacha que tendremos que equiparnos.
Cogemos la Potion y nos curamos con "Use Potion"
Una al norte y una al este.

Zona Hall:
Cogemos la manzana del suelo.
norte

Kitchen:
Cogemos el Cheese.
sur, este, sur

Treasure room:
Cogemos el "Ruby"
no lo usamos ya que solo se puede añadir en un arma y luego lo perderemos.
norte y 2 al este

Throne room:
Luchamos contra el troll, recibimos de él la llave y cogemos la espada del suelo con "Take Claymore" y la equipamos con "Use Claymore".
usamos el ruby con la Claymore equipada aumentando asi el ataque
curamos con "Use Cheese/Apple"
5 al Oeste, esta vez con la llave podremos atravesar la puerta.

Courtyard:
Derrotar al dragon con "attack"

FIN

*****************************************************************************************************

Mis principales dificultades a la hora de programar ciertas cosas fueron el hecho de tener dos objetos en una misma habitación o el
hacer que el arma potenciada con la gema no pierda la potenciacion al equipar otro arma y volver a equipar la potenciada.
Al principio plantee un npc que era el que te daba la poción y un sistema de puertas no bloqueadas que se tenían que abrir previamente
antes de poder entrar en una habitación pero debido al estrecho margen de tiempo que tenía preferí centrarme en los requerimentos 
básicos del programa.
