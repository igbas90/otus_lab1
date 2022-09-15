
 Запускаем или через skaffold или последовательно deployment -> service -> ingress 

- роут health/ обращается к сервису
- роут otusapp/{student_name}/* форвардит туда же, куда и health