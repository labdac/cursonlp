Clase sobre Sentiment Analysis - prototipo

Axiomas del camino feliz
* en inglés
* sin problemas de parseo/POS tagging/etc
* sin poner en producción

Modelo más sencillo
* el histórico de puntajes a palabras y sumar eso
problemas de esto (ambiguedad, construcciones negativas)

Modelo un poco más copado
* word embeddings y luego NB/SVM/otra cosa

Aspect-based sentiment analysis
* para el caso feliz, teniendo ya anotadas los POS y dependencias
de las palabras
https://www.aclweb.org/anthology/W17-5202
https://cs224d.stanford.edu/reports/WangBo.pdf


Cosas para copiar
- https://github.com/abdulfatir/twitter-sentiment-analysis
tiene varios modelos sencillos
- curso de richard socher

Datos posible
- twitter al respecto de un tema sencillo de opinar
la selección p.ej., no tanto algo político
- antes y después notre dame?
- aspect-based: SemEval-2015

Métricas
- precision, recall, accuracy
- krippendorff's alpha

