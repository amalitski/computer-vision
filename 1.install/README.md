# Установка и настройка рабочего окружения

Цель:
Собрать свой docker контейнер для работы с моделями глубокого обучения.

Необходимо установить и настроить рабочее окружение:

- Установить и настроить Docker.
- Если используете NVIDIA GPU, то также установить nvidia-docker.
- Собрать и запустить контейнер с Ubuntu 18.04 (или выше).
- Развернуть в контейнере PyTorch, TensorFlow, JupyterLab, OpenCV.
- В Google Colab запросите GPU.


---

# Запуск

`docker-compose up -d --build`

# Версии

```
# pip list | grep torch
torch                   1.9.0
torchvision             0.10.0
```

```
# pip list | grep tensorflow
tensorflow              2.5.0
tensorflow-estimator    2.5.0
```