# Proyecto easyCustomerFeedback
<strong><i>Por Fran Gámez</i></strong>

![alt EasyCustomerFeedback Project](annotated_image-1024x683.jpg?raw=true "Easy Customer Feedback")

<p><strong>EasyCustomerFeedback </strong>es un nuevo <strong>proyecto de reciente creación</strong> que tiene como objetivo permitir a cualquier empresa o persona organizadora de cualquier tipo de evento recopilar información de sus clientes basadas en gestos a través de un dispositivo de bajo coste.</p>

<p>El sistema es capaz de reconocer en <strong>tiempo real</strong> los gestos de las personas que pasan por delante de una cámara, estimar si es un gesto de aprobación o desaprobación e incluso predecir el género, edad y el estado de ánimo.  Toda la información inferida en tiempo real <strong>se almacena en la nube</strong> para su posterior consulta y explotación.</p>

<p>Todo el proceso <strong>apenas requiere esfuerzo ni espera</strong> por parte de los invitados que ahora podrán dejar su valoración en apenas un par de segundos.  Además, la valoración es totalmente anónima ya que no se recopila en ningún momento datos personales o sensibles de las personas que dejan su opinión a través de este novedoso sistema.</p>

<p>Por su lado el organizador del evento podrá acceder a un <strong>informe </strong>donde se resume la cantidad de valoraciones recibidas por los invitados o clientes.</p>

<p>La <strong>visión y misión del proyecto</strong> es ofrecer una plataforma de código abierto y transparente de valoración universal que cualquiera pueda usarlo de forma fácil y barata y que aporte valor real para el público en general y no solo a empresas.  El sistema podría ser utilizado para un sinfín de propósitos:</p>

<ul><li>Valoración de <strong>lugares públicos</strong>: parques, monumentos,...</li><li>Valoración de <strong>servicios públicos</strong>: a la salida de un organismo público para valorar la atención recibida (hospitales, INEM, Agencia tributaria,...)</li><li>Valoración de restaurantes, hoteles, gimnasios, medios de transportes...</li><li>Eventos <strong>particulares</strong>: bodas, comuniones, bautizos, cumpleaños,...</li><li>Eventos <strong>corporativos</strong>: congresos, convenciones, team building,...</li></ul>

<p>Y todas esas valoraciones estarían disponibles en la nube y accesibles para el público en general.</p>

# Arquitectura técnica
El proyecto tiene 3 partes bien diferenciadas:
<ul>
  <li><strong>Aplicación IoT</strong> capaz de ejecutarse en diferentes dispositivos de bajo coste como una <strong>Raspberry PI</strong> o <strong>dispositivos Android</strong>.  Es la aplicación responsable de capturar las imágenes y con técnicas de visión por computador e inteligencia artificial detectar las personas y sus gestos.
    <p><i>Tecnologías y frameworks</i>: Python, Pandas, Numpy, Scikit-Learn, MediaPipe, DeepFace.</p>
  </li>
  <li><strong>Aplicación dashboard</strong> donde se publican los informes de cada evento para que los organizadores puedan conocer la satisfacción de sus invitados.
  <p><i>Tecnologías y frameworks</i>: React.js, Core-UI Template.</p>
  </li>
  <li><strong>API</strong>. Publica los servicios requeridos tanto para las aplicaciones IoT como para el dashboard de consulta de informes. Permite crear y autorizar eventos y recopilar los datos en la nube.
   <p><i>Tecnologías y frameworks</i>: PHP.  En el futuro está API estará alojada en Microsoft Azure.</p>
  </li>
</ul>

# Sponsor
![alt eventicrea](https://eventicrea.es/wp-content/uploads/2017/01/eventicrea_logo-1.jpg?raw=true "eventiCrea")

<strong>eventicrea</strong> es una empresa de organización de eventos corporativos y sociales que está siendo pionera en la implementación de este novedoso servicios en sus clientes.

# Prueba beta-cerrada
¿Quieres probar el servicio?

Ahora puedes probar el servicios en una máquina <strong>Windows</strong> o <strong>Mac</strong> con webcam y conexión a internet. En el siguiente enlace puedes encontrar toda la información necesaria para darte de alta y configurar tu equipo de forma rápida y sencilla.

[Prueba el servicio EasyCustomerFeedback](https://eventicrea.es/proyecto-easycustomerfeedback/)
