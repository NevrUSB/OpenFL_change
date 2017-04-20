# OpenFL_change
haxelib dev

Rtree
Rjrtee

DrawTree
http://docs.openfl.org/openfl/display/Graphics.html

lineTo (x:Float, y:Float):Void
Draws a line using the current line style from the current drawing position to(x, y); the current drawing position is then set to(x, y). If the display object in which you are drawing contains content that was created with the Flash drawing tools, calls to the lineTo() method are drawn underneath the content. If you call lineTo() before any calls to the moveTo() method, the default position for the current drawing is(0, 0). If any of the parameters are missing, this method fails and the current drawing position is not changed.

Parameters:

x	
A number that indicates the horizontal position relative to the registration point of the parent display object(in pixels).
y	
A number that indicates the vertical position relative to the registration point of the parent display object(in pixels).
moveTo (x:Float, y:Float):Void
Moves the current drawing position to(x, y). If any of the parameters are missing, this method fails and the current drawing position is not changed.

Parameters:

x	
A number that indicates the horizontal position relative to the registration point of the parent display object(in pixels).
y	
A number that indicates the vertical position relative to the registration point of the parent display object(in pixels).
__________________
https://github.com/NevrUSB/jonas-haxe/blame/master/src/jonas/ds/RTree.hx
https://github.com/jonasmalacofilho/jonas-haxe/blob/master/src/jonas/ds/RTree.hx

http://haxe.org/manual/haxelib-using.html
http://forum.haxeflixel.com/topic/38/type-not-found-nmepreloader
https://medium.com/kodemint-technologies/haxe-lime-openfl-ec9c2784aaa8
http://www.gamefromscratch.com/post/2016/07/12/OpenFL-4-Released.aspx
http://blog.zame-dev.org/openfl-extension-in-10-steps/
http://www.cyberforum.ru/opengl/thread1378633.html
https://play.google.com/store/apps/details?id=com.pixelsyntax.openfltest
https://hghltd.yandex.net/yandbtm?fmode=inject&url=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.pixelsyntax.openfltest&tld=ru&lang=ru&la=1478230272&tm=1492685761&text=display%20openfl%20%20stage%20sprite&l10n=ru&mime=html&sign=ced9efae0ffb3c0a4ab9a46a07b63df0&keyno=0
https://msdn.microsoft.com/en-us/windows/hardware/drivers/display/supporting-opengl-enhancements
https://habrahabr.ru/post/243199/
https://github.com/azrafe7/hxAABBTree

http://docs.openfl.org/openfl/display/Graphics.html
http://docs.openfl.org/openfl/display/index.html
http://docs.openfl.org/openfl/display/Stage.html?


https://github.com/jonasmalacofilho/jonas-haxe/blob/master/src/jonas/ds/RjTree.hx
https://github.com/NevrUSB/jonas-haxe/blob/master/src/jonas/ds/RTree.hx
https://github.com/jonasmalacofilho/jonas-haxe/tree/master/src/jonas/ds   (rtree haxe)
r(-)tree haxe
rtree haxe
openfl stage
haxe lib dev openfl path
display opengl  stage sprite различия
http://help.adobe.com/ru_RU/FlashPlatform/reference/actionscript/3/flash/display/DisplayObject.html
http://www.nestor.minsk.by/kg/2011/42/kg14208.html

!!!!!!!!!!!!!!!!!!!!!!!!!!!!
lineto
1) расширение прямоугольника при изменении х и у (привдение к глобальным координатом)
---отслеживать список и проверять на правильность работы Ртри (более точную затратную проверку)

изменение прям в ртри при изменении дисплей обджекта

изменение координат при изменении прямоугольников

