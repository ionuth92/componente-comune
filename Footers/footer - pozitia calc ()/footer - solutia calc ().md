Solu?ia calc()
Op?iunea B folose?te func?ia calc() �ncorporata. Aceasta metoda se bazeaza pe:

�mpachetarea tuturor elementelor �ntr-un container cu excep?ia subsolului,
setarea unei �nal?imi fixe pentru subsol ?i
calcularea �nal?imii containerului cu con?inut ca ��nal?ime completa a zonei de vizualizare - �nal?ime subsol�.

Elementul de baza al acestei solu?ii este func?ia calc(). Aceasta poate calcula �n mod dinamic �nal?imea pentru .content prin scaderea �nal?imii subsolului din �nal?imea totala a zonei de vizualizare. �n acest fel, .content va �mpinge �ntotdeauna subsolul �n partea de jos a zonei de vizualizare.

Totu?i, aceasta metoda are aceea?i limitare ca ?i cea anterioara: aceasta func?ioneaza daca subsolul tau are o �nal?ime fixa. Din nou, nu este ceva capital, dar trebuie sa fii con?tient de asta.