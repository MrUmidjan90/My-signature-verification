# My-signature-verification

- [ ] Подготовить список задач
    
     1) Подготовить базу изображений 
     2) Загрузить изображение 
     3) Бинаризовать изображение
     4) бинаризация подписи.
     5) извлечь координаты черных пикселей (облако в 2D): т.е. коорд-ты всех ненулевых пикселей.
     6) подать их на PCA, получить 2 собственных числа и 2 вектора.
     7) выбрать вектор соответствующий большему числу — он (вектор) определяет основная ось.
     8) вычислить угол поворота этой оси относительно горизонтали и повернуть облако точек из шага 2.
     9) вырезать описывающий точки прямоугольник, обрезав тонкие концы линий.
     10) выполнить масштабирование прямоугольника до заданного размера NxM — это шаблон подписи.
    
