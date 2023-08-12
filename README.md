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

#### Запуск 

![тестирование chart](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/fd0ec6ba-3597-4939-9df1-a62b9f2140d0)

------
### Задание 2. Запустить две версии в разных неймспейсах

1. Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.
2. Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.
3. Продемонстрируйте результат.


### Ответ

#### ![Chart файлы](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/tree/037e2d9d991979c5949c78401e9d2d8c7dadc6d9/12.10.2)

#### Создание namespase

![создание nemespaces](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/c68d5d89-5be8-411b-8dee-541c84a4b78d)

#### создание дополнительных файлов значений

![добавление файлов значений](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/c974f2be-2292-4a63-87a1-b2cbc0e5988f)

#### Развертывание первой версии приложения

![1 версия приложения](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/4968c8fa-7556-4e4c-977d-1a66e57aa476)

#### Развертывание первой версии приложения

![1 версия приложения](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/97d21063-d943-4192-8b19-22eac3ada01f)

#### Развертывание второй версии приложения

![2 версии приложения](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/0ce18258-cfa7-46f0-97cc-a092df384df8)

#### Развертывание третьей версии приложения

![3 версия приложения](https://github.com/ALEMOLOKOV/13.5_K8S_Aleksandr_Molokov/assets/109212419/8b991705-1080-45c9-bb9f-73b0cf0ffbba)
