# -Домашнее задание к занятию «Базовые объекты K8S»

## Задание 1. 
Создать Pod с именем hello-world
Создать манифест (yaml-конфигурацию) Pod.
Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
Подключиться локально к Pod с помощью kubectl port-forward и вывести значение (curl или в браузере).

### Ответ
 - [pod](https://github.com/Nano-prototip/-K8S-/blob/main/pod.yml).

## Задание 2. 
Создать Service и подключить его к Pod
Создать Pod с именем netology-web.
Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
Создать Service с именем netology-svc и подключить к netology-web.
Подключиться локально к Service с помощью kubectl port-forward и вывести значение (curl или в браузере).

### Ответ

<img width="858" height="391" alt="03" src="https://github.com/user-attachments/assets/f37078cd-39d4-432b-8c43-7310ed7e65fd" />
<img width="858" height="391" alt="03" src="https://github.com/user-attachments/assets/f37078cd-39d4-432b-8c43-7310ed7e65fd" />

- [service](https://github.com/Nano-prototip/-K8S-/blob/main/service.yml).
