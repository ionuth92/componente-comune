Solu?ia calc()
Op?iunea B folose?te func?ia calc() încorporata. Aceasta metoda se bazeaza pe:

împachetarea tuturor elementelor într-un container cu excep?ia subsolului,
setarea unei înal?imi fixe pentru subsol ?i
calcularea înal?imii containerului cu con?inut ca „înal?ime completa a zonei de vizualizare - înal?ime subsol”.

Elementul de baza al acestei solu?ii este func?ia calc(). Aceasta poate calcula în mod dinamic înal?imea pentru .content prin scaderea înal?imii subsolului din înal?imea totala a zonei de vizualizare. În acest fel, .content va împinge întotdeauna subsolul în partea de jos a zonei de vizualizare.

Totu?i, aceasta metoda are aceea?i limitare ca ?i cea anterioara: aceasta func?ioneaza daca subsolul tau are o înal?ime fixa. Din nou, nu este ceva capital, dar trebuie sa fii con?tient de asta.