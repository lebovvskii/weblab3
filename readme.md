<h2>Как я делал лабу:</h2>
<ol>
 <li>Скачал docker</li>
 <li>
  Ввёл команду:
    <code>
      docker run -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin jboss/keycloak
    </code>
 </li>
 <li>получил screen1.png</li>
 <li>авторизовался (screen2.jpeg)</li>
 <li>создал клиента (screen3.jpeg)</li>
 <li>создал скоуп</li>
 <li>создал группу</li>
 <li>cоздал юзера </li>
 <li>добавил роль </li>
 <li>
    после того как я добавил группе в которой есть мой юзер роль new_role, юзер автоматически   получил роль
 </li>
 <li>Постманом тыык  (см. screen4.jpeg)</li>
 <li>Ещё раз тыык  (см. screen5.jpeg)</li>
</ol>

<p>
  Резервное копирование делал через cron, порт был открыт
</p>
