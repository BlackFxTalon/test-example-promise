promise syntax real world example - это пример-демонстрация работы promises в действии. Здесь пример состоит в том, что с помощью метода fetch() берем картинку, затем берем blob картинки, подставляем в качестве атрибута src, создаем элемент img, и подставляем туда. Здесь я попробовал метод fetch(), и саму концепцию promises - методы then(), если promises перешел в статус resolve или fulfilled, и метод catch() для обработки ошибок promises в статусе rejected. Также написал два примера - промисы без цепочки (с каждой новой переменной в объявлении) и с цепочкой (с одной переменной, что делает код компактнее). Cсылка netlify-server - .