# Servidor de Reconocimiento Facial
Este repositorio contiene una implementación de código del lado del servidor para realizar reconocimiento facial utilizando modelos de deep learning.
El servidor permite a los clientes enviar imágenes y recibir predicciones sobre las identidades de las caras presentes en esas imágenes.
## Características
1. Reconocimiento Facial: El servidor utiliza algoritmos de aprendizaje profundo para reconocer caras en imágenes y proporciona predicciones sobre sus identidades.
2. Arquitectura Cliente-Servidor: Los clientes pueden enviar imágenes al servidor a través de llamadas API y recibir predicciones como respuesta.
3. Escalabilidad: El servidor está diseñado para manejar múltiples solicitudes de clientes simultáneamente, lo que lo hace adecuado para implementaciones en entornos de producción.
4. Gestión de Modelos: El código incluye funcionalidades para administrar y actualizar el modelo de reconocimiento facial.
5. Registro y Monitoreo: El servidor registra eventos y errores, lo que permite el monitoreo y la solución de problemas.
## Requisitos

1. Python 3.x
2. Flask
3. TensorFlow
4. OpenCV
