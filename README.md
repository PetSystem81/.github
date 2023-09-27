# Análisis de requerimientos

## Índice
  - [Contexto](#contexto)
  - [Stakeholders Involucrados](#stakeholders-involucrados)
  - [Fuentes de Información Primarias](#fuentes-de-información-primarias)
    - [Entrevista con Dra. Susana](#1-entrevista-con-dra-susana)
    - [Entrevista con Sra. Maria](#2-entrevista-con-sra-maria)
    - [Encuesta a Pacientes](#3-encuesta-a-pacientes)
  - [Principales desafíos y problemas en el proceso actual](#principales-desafíos-y-problemas-en-el-proceso-actual)
  - [Informe de Ingeniería de Requisitos](#informe-de-ingenier%C3%ADa-de-requisitos-para-la-digitalizaci%C3%B3n-del-proceso-de-reserva-de-citas-en-el-consultorio-veterinario-de-la-dra-susana)
    - [Resumen Ejecutivo]()
    - [Requisitos Funcionales]()
      - [Reserva de Citas en Línea]()
      - [Administración y Gestión]()
      - [Comunicación y Soporte]()
    - [Requisitos No Funcionales](#requisitos-no-funcionales)
    - [Requisitos Adicionales](#requisitos-adicionales)
    - [Conclusiones](#conclusiones)

## Contexto

En la actualidad, el consultorio veterinario, bajo la dirección de la **Dra. Susana**, gestiona su proceso de reserva de citas exclusivamente a través de llamadas telefónicas, donde la **Sra. Maria**, su secretaria, atiende las solicitudes de los clientes. Sin embargo, en busca de una modernización y para mejorar la experiencia tanto de los pacientes como del personal, se ha planteado la ambiciosa meta de digitalizar este proceso. El objetivo principal es migrar hacia una plataforma web que permita a los clientes realizar sus reservas de citas de manera sencilla y eficiente, garantizando que queden agendados de manera efectiva.

### Stakeholders Involucrados:

1. **Dra. Susana:** La propietaria del consultorio veterinario y la principal interesada en la digitalización del proceso de reserva de citas.

2. **Sra. Maria:** La secretaria de la Dra. Susana, quien actualmente maneja las reservas de citas a través de llamadas telefónicas.

3. **Pacientes del consultorio:** Los usuarios finales que necesitarán utilizar la aplicación para agendar citas.

### Fuentes de Información Primarias:

#### 1. **Entrevista con Dra. Susana:**

Tengo ciertas necesidades y expectativas claras en lo que respecta a la aplicación que se desarrollará para digitalizar el proceso de reserva de citas en mi consultorio veterinario. Aquí están mis principales necesidades y expectativas:

- **_Facilidad de Uso:_** Necesito que la aplicación sea intuitiva y fácil de usar tanto para mi secretaria, la Sra. Maria, como para los pacientes que programarán citas. No queremos que la digitalización agregue complicaciones al proceso.
- **_Gestión de Citas Eficiente:_** Espero que la aplicación permita gestionar las citas de manera eficiente. Debe mostrar un calendario claro con disponibilidad de horarios y permitir la reserva de citas de manera rápida y sencilla.
- **_Acceso en Línea:_** Una de mis expectativas principales es que los pacientes puedan acceder a la aplicación en línea desde sus dispositivos, ya sea una computadora de escritorio o un dispositivo móvil. Esto les dará flexibilidad para programar citas en cualquier momento y desde cualquier lugar.
- **_Notificaciones y Recordatorios:_** Me gustaría que la aplicación envíe notificaciones y recordatorios automáticos a los pacientes para reducir la tasa de cancelaciones y asegurarse de que lleguen puntualmente a sus citas.
- **_Historial de Citas y Registros de Pacientes:_** La aplicación debe tener la capacidad de mantener un historial de citas y registros de pacientes. Esto nos ayudará a llevar un seguimiento adecuado de la atención médica de cada mascota.
- **_Seguridad de los Datos:_** La seguridad de los datos es una preocupación importante. Espero que la aplicación garantice la privacidad de la información de los pacientes y cumpla con las regulaciones de protección de datos.
- **_Capacidad de Gestión:_** Como propietaria, necesito herramientas de gestión que me permitan supervisar y administrar el sistema. Esto podría incluir la capacidad de agregar o modificar horarios, personal y recursos.

- **_Soporte Técnico y Mantenimiento:_** Deseo que el equipo de desarrollo proporcione un sólido soporte técnico y esté disponible para cualquier mantenimiento o actualización necesarios en el futuro.

#### 2. **Entrevista con Sra. Maria:**

El proceso actual de gestión de citas se realiza de la siguiente manera:
Proceso de Reserva de Citas por Teléfono:

- **_Recepción de Llamadas:_**

  1. Mi principal tarea es responder a las llamadas telefónicas entrantes de los clientes que desean reservar citas para sus mascotas.

- **_Verificación de Disponibilidad:_**

  1. Consulto nuestra agenda física para verificar la disponibilidad de horarios para citas.
  2. Anoto los horarios disponibles y ofrezco opciones a los clientes según su preferencia de tiempo y la naturaleza de la cita.

  - **_Recopilación de Información del Cliente:_**

    1. Solicito y registro la siguiente información del cliente:
       - Nombre completo del dueño de la mascota.
       - Nombre de la mascota.
       - Especie y raza de la mascota.
       - Edad de la mascota.
       - Detalles del motivo de la cita.
       - Número de teléfono de contacto.
    2. Aseguro que la información se registre con precisión y de manera legible para futuras referencias.

  - **_Confirmación de la Cita:_**

    1. Al finalizar la reserva de la cita, confirmo la cita con el cliente, proporcionando detalles como la fecha, hora y motivo de la cita.
    2. Animo a los clientes a anotar la fecha en sus calendarios y recordarla.

  - **_Recordatorios de Citas:_**

    1. Un día antes de la cita, llamo a los clientes para recordarles la cita programada y confirmar que todavía pueden asistir.
    2. Esto ayuda a reducir las cancelaciones de última hora y asegura una alta asistencia a las citas.

  - **_Registro Manual:_**

    1. Mantengo un registro manual de todas las citas en una agenda física y una hoja de cálculo en la computadora.
    2. La información incluye la fecha y hora de la cita, el nombre del cliente, el nombre de la mascota y el motivo de la cita.

  - **_Atención a Preguntas y Consultas:_** Además de las reservas de citas, estoy disponible para responder preguntas generales de los clientes sobre nuestros servicios y proporcionar información básica sobre el consultorio.

  - **_Atención a Emergencias:_**
    En casos de emergencias veterinarias, transfiero de inmediato las llamadas a la Dra. Susana o al personal de atención de emergencias.

#### 3. **Encuesta a Pacientes:**

   - **Paciente 1:** Laura (Dueña de un gato llamado Whiskers):

     - _Opinión sobre la reserva de citas en línea:_ "La opción de reserva de citas en línea sería genial para mí. A veces, durante el día, no puedo realizar llamadas telefónicas, pero podría programar una cita rápida en mi computadora en el trabajo. Sería mucho más conveniente."

     - _Disponibilidad de Horarios:_ "Me gustaría que la aplicación muestre los horarios disponibles en tiempo real para que pueda elegir el mejor momento para Whiskers sin tener que esperar a que me llamen de vuelta."

     - _Característica Adicional Deseada:_ "Sería útil si la aplicación pudiera mostrar las tarifas de los servicios y si pudiéramos pagar en línea después de reservar una cita. Esto me ayudaría a planificar y gestionar mejor los gastos de atención veterinaria."

   - **Paciente 2:** Juan (Dueño de un perro llamado Rocky):

     - _Opinión sobre la reserva de citas en línea:_ "Me gusta la idea de reservar citas en línea, especialmente en momentos en que no puedo hacer llamadas telefónicas, como durante mi trabajo."

     - _Disponibilidad de Horarios:_ "Sería fantástico si la aplicación mostrara la disponibilidad de horarios de la Dra. Susana y permitiera seleccionar rápidamente la fecha y hora que mejor se adapte a mi horario."

     - _Característica Adicional Deseada:_ "Me gustaría recibir notificaciones automáticas sobre las citas y recordatorios a través de la aplicación. Esto me ayudaría a no olvidar las citas de Rocky."

   - **Paciente 3:** Vanessa (Dueña de un loro llamado Max):

     - _Opinión sobre la reserva de citas en línea:_ "Sería muy conveniente poder reservar citas en línea, ya que tengo un horario de trabajo ocupado y a veces se me dificulta llamar por teléfono."

     - _Disponibilidad de Horarios:_ "Me gustaría ver los horarios disponibles y tener la opción de elegir la hora que funcione mejor para mí y para Max."

     - _Característica Adicional Deseada:_ "Sería útil si la aplicación incluyera un espacio donde pudiera proporcionar información adicional sobre la salud de Max antes de la cita, como síntomas o preocupaciones específicas."

   - **Paciente 4:** Carlos (Dueño de dos conejos llamados Salt y Pepper):

     - _Opinión sobre la reserva de citas en línea:_ "La reserva de citas en línea sería estupenda para mí. A veces tengo que esperar mucho tiempo en la línea telefónica, y sería más rápido si pudiera hacerlo en línea."

     - _Disponibilidad de Horarios:_ "Es importante para mí que la aplicación muestre los horarios de la Dra. Susana con anticipación, especialmente los fines de semana, ya que trabajo de lunes a viernes."

     - _Característica Adicional Deseada:_ "Me gustaría que la aplicación incluyera una función de chat en vivo o una línea directa de contacto con el consultorio para preguntas rápidas sobre el cuidado de mis conejos."
    
Estas opiniones y preferencias de los pacientes resaltan la conveniencia de la reserva de citas en línea, la importancia de la disponibilidad de horarios en tiempo real y la necesidad de características adicionales que mejoren la comunicación y la gestión de la atención veterinaria.

### Principales desafíos y problemas en el proceso actual:

1. **Registro Manual:**

   - El proceso de registro manual de las citas en una agenda física y una hoja de cálculo en la computadora puede ser propenso a errores humanos, como duplicación de citas o errores de registro.
   - Esto puede dar lugar a confusiones y problemas en la gestión de las citas, lo que podría afectar la eficiencia y la satisfacción del cliente.

2. **Limitación en la Disponibilidad de Horarios:**

   - La verificación de la disponibilidad de horarios depende de la agenda física, lo que podría limitar la capacidad de ofrecer horarios de manera rápida y precisa.
   - Los clientes podrían sentirse frustrados si no pueden obtener horarios que se adapten a sus necesidades debido a limitaciones en la disponibilidad.

3. Comunicación y Recordatorios Manuales:

   - Los recordatorios de citas se realizan de manera manual, lo que implica un gasto considerable de tiempo y esfuerzo.
   - Puede haber casos en los que se olvide realizar los recordatorios o se realicen de manera inconsistente.

4. **Registro de Datos Limitado:**

   - La información de los pacientes y las citas se registra de manera básica en una hoja de cálculo, lo que limita la capacidad de llevar un seguimiento detallado del historial de atención de las mascotas.
   - Esto podría dificultar la prestación de un servicio más personalizado y eficiente.

5. **Tiempo de Espera en Llamadas Telefónicas:**

   - Los clientes pueden experimentar tiempos de espera en las llamadas telefónicas cuando intentan reservar citas, especialmente durante los períodos de alta demanda.
   - Esto podría resultar en una experiencia incómoda para los clientes.

6. **Potencial para Cancelaciones de Última Hora:**

   - A pesar de los recordatorios de citas, aún existe la posibilidad de que los clientes cancelen las citas de última hora, lo que puede generar huecos en la agenda que podrían haberse llenado con anticipación.

7. **Acceso Limitado a la Información:**
   - La información de las citas y los registros de pacientes solo está disponible en la computadora de la Sra. Maria, lo que limita la accesibilidad para otros miembros del equipo o para consultas fuera de la oficina.

Estos desafíos y problemas en el proceso actual resaltan la necesidad de una solución más eficiente y automatizada para la reserva de citas, como una aplicación web, que pueda abordar estas limitaciones y mejorar la experiencia tanto para la Sra. Maria como para los clientes del consultorio veterinario.


## Informe de Ingeniería de Requisitos para la Digitalización del Proceso de Reserva de Citas en el Consultorio Veterinario de la Dra. Susana

### Resumen Ejecutivo

Este informe detalla los requisitos clave para el desarrollo de una aplicación web que permita la reserva de citas en línea en el consultorio veterinario de la Dra. Susana. La digitalización del proceso de reserva de citas tiene como objetivo mejorar la eficiencia, la accesibilidad y la comodidad tanto para el personal del consultorio como para los clientes.

El proceso de ingeniería de requisitos se basó en la recopilación de información de diversas fuentes, incluyendo entrevistas con la Dra. Susana y la Sra. Maria, así como la opinión de pacientes ficticios. Además, se analizaron enfoques comunes utilizados por otros consultorios veterinarios y servicios médicos similares que ofrecen reservas de citas en línea.

### Requisitos Funcionales

#### Reserva de Citas en Línea

1. **Reserva de Citas:** Los clientes deben poder reservar citas en línea a través de la aplicación, proporcionando detalles como la fecha preferida, la hora, el motivo de la cita, el nombre del dueño de la mascota y el nombre de la mascota.

2. **Calendario Interactivo:** La aplicación debe incluir un calendario interactivo que muestre la disponibilidad de horarios en tiempo real y permita a los clientes seleccionar fácilmente una cita disponible.

3. **Mensajes de Confirmación y Recordatorios:** La aplicación debe generar automáticamente mensajes de confirmación después de la reserva y recordatorios antes de la cita a través de correos electrónicos o mensajes de texto.

4. **Perfiles de Usuario:** Los clientes deben tener la opción de crear perfiles de usuario para acceder a su historial de citas, registros de salud de las mascotas y detalles de facturación.

#### Administración y Gestión

1. **Gestión de Horarios:** La aplicación debe permitir a la Dra. Susana y su equipo gestionar y actualizar los horarios disponibles, incluyendo la capacidad de bloquear horarios para vacaciones o emergencias.

2. **Registro de Datos de Pacientes:** La aplicación debe registrar información detallada de las mascotas y su historial de atención médica, permitiendo a la clínica llevar un seguimiento adecuado de cada paciente.

3. **Notificaciones de Cambios y Cancelaciones:** La aplicación debe notificar automáticamente a la clínica y al cliente en caso de cambios o cancelaciones de citas.

#### Comunicación y Soporte

1. **Chat en Vivo y Soporte en Línea:** La aplicación debe ofrecer un sistema de chat en vivo y una línea directa de atención al cliente en línea para brindar asistencia rápida a los clientes.

2. **Acceso Móvil:** La aplicación debe ser responsive y permitir a los clientes acceder y reservar citas desde dispositivos móviles.

3. **Pago en Línea:** Los clientes deben tener la opción de realizar pagos en línea después de reservar una cita.

### Requisitos no Funcionales

1. **Seguridad de Datos:** La aplicación debe garantizar la seguridad de los datos personales y médicos de los clientes, cumpliendo con las regulaciones de protección de datos.

2. **Diseño Intuitivo:** La interfaz de usuario debe ser intuitiva y fácil de usar, tanto para el personal de la clínica como para los clientes.

3. **Disponibilidad en Tiempo Real:** La aplicación debe mostrar la disponibilidad de horarios en tiempo real para evitar conflictos de reservas.

4. **Notificaciones Automáticas:** Los mensajes de confirmación y recordatorios deben enviarse automáticamente para reducir cancelaciones y no asistencias.

5. **Personalización:** La aplicación debe ser adaptable a las necesidades específicas del consultorio de la Dra. Susana.

### Requisitos Adicionales

1. **Tarifas de Servicios:** La aplicación debe mostrar las tarifas de los servicios ofrecidos en el consultorio veterinario.

2. **Registro de Información Adicional del Paciente:** Los clientes deben poder proporcionar información adicional sobre la salud de sus mascotas antes de la cita.

### Conclusiones

La digitalización del proceso de reserva de citas en el consultorio veterinario de la Dra. Susana permitirá mejorar significativamente la eficiencia y la satisfacción de los clientes. Cumplir con estos requisitos funcionales y no funcionales asegurará que la aplicación sea intuitiva, segura y eficaz, brindando una experiencia de reserva de citas en línea excepcional para todos los involucrados.

