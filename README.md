# microservices2024
Learning microservices course

В проекте представлены манифесты Deployment, Service, Ingress, которые могу быть запущены командой kubectl apply -f
Приложение отвечает по адресу http://arch.homework/health
Также предусмотрено перенаправление запросов в формате arch.homework/otusapp/(.*)/(.*) на http://arch.homework/health
