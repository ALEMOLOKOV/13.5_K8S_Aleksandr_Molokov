# 13.5_K8S_Aleksandr_Molokov

### Задание 1. Подготовить Helm-чарт для приложения

1. Необходимо упаковать приложение в чарт для деплоя в разные окружения. 
2. Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.
3. В переменных чарта измените образ приложения для изменения версии.


### Ответ

#### ![Chart Файлы](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/commit/4fea76ec1d1828e68959e3dd0dfbbcc102d87374)

#### Установка Helm

![установка helm](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/46dfbc6b-6b3b-40a2-9129-d5df63afde0d)

#### Создание Chart

![создание chart](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/98a56d3a-7fc2-4647-a71f-f02d0ea29052)

#### Создание шаблона Helm template my-helm-chart

![helm template my-helm-chart](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/28fa3053-a5d1-43d9-b905-699328e0286a)

![helm template my-helm-chart1](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/04e764c1-1b8a-4aba-a5db-5a533964f14f)


------
### Задание 2. Запустить две версии в разных неймспейсах

1. Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
2. Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
3. Продемонстрируйте результат.


### Ответ

