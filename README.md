# task-manager
# python, flask, html, js, css
simple task manager using flask 
tested via Postamn.
для создания новой задачи используется метод POST с раутером add:
http://127.0.0.1:5000/add
для получения списка задач используется метод GET c http://127.0.0.1:5000/
для удаления задач из списка используется метод DELETe с http://127.0.0.1:5000/delete/id
чтобы отметить задачу, как завершенную используется метод GET/POST c http://127.0.0.1:5000/update/id
для обновления задачи в списке используется метод GET/POST c http://127.0.0.1:5000/update/id

для запуска приложения требуется запустить python app.py и перейти на http://127.0.0.1:5000/add
P.S. использованы готовые компоненты базового фронтенда - могут быть в перебое работы приложения

