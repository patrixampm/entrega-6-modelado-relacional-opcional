# Entrega 6: Modelado Relacional

## Parte Opcional

He realizado este modelo entidad-relación siguiendo la siguiente lógica:

- He dejado la mayoría de las tablas tal y como estaban ya que la mayoría de relaciones entre las distintas entidades siguen igual que en la entrega obligatoria.

- El requerimiento de crear una estructura jerárquica lo he resuelto en la propia tabla de temática, donde una temática puede (opcional) tener varias subcategorías, pero cada subcategoría solo puede y debe tener una temática padre.

- El requerimiento de tener vídeos publicos y privados estaba ya resuelto en la parte obligatoria de esta entrega. Cada vídeo tiene un campo booleano donde se especifica si es gratis o de pago. De esta manera se puede, de forma sencilla, restringir el acceso de los usuarios en función de vídeo.
