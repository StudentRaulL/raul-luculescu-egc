# Laborator 9 - Texturare
Raul Luculescu, 3132a

Întrebări și răspunsuri:
* Utilizați pentru texturare imagini cu transparență și fără. Ce observați?
 Când utilizăm o imagine transparentă pentru texturare, pixelii transparenți sunt colorați alb sau ce culoare am ales.
* Ce formate de imagine pot fi aplicate în procesul de texturare în OpenGL?
 OpenGL suportă mai multe formate de imagine, cum ar fi: BMP, PNG, JPEG, TGA sau DDS.
* Specificați ce se întâmplă atunci când se modifică culoarea (prin manipularea canalelor RGB) obiectului texturat.
 Când modificăm culoarea obiectului texturat, culorile din textura acestuia se alterează după cum am manipulat noi canalele RGB.
* Ce deosebiri există între scena ce utilizează obiecte texturate în modul iluminare activat, respectiv dezactivat?
 Când iluminarea este activată, obiectul nostru are umbre, zone mai luminoase sau mai întunecate în funcție de poziția și sursei de lumină și de textura folosită. Fără luminare, obiectul poate părea 2D.
 