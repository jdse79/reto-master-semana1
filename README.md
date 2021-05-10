# Reto Master Semana 1

## Computo en la nube.

Es la entrega de servicios informáticos a través de Internet, lo que se conoce como la nube. Estos servicios incluyen servidores, almacenamiento, bases de datos, redes, software, análisis e inteligencia. La informática en la nube ofrece una innovación más rápida, recursos flexibles y economías de escala.

Algunas ventajas de usar el computo en la nube son:

- Confiabilidad: en función del contrato de nivel de servicio que elija, las aplicaciones basadas en la nube pueden proporcionar una experiencia de usuario continua sin tiempo de inactividad perceptible, aunque se produzcan errores.
- Escalabilidad: las aplicaciones en la nube se pueden escalar de dos maneras, sacando partido al mismo tiempo del escalado automático:
- Verticalmente: la capacidad informática se puede aumentar si se agrega RAM o CPU adicionales a una máquina virtual.
- Horizontalmente: la capacidad informática se puede aumentar si se agregan instancias de un recurso, como máquinas virtuales adicionales a la configuración.
- Elasticidad: las aplicaciones basadas en la nube se pueden configurar para que siempre tengan los recursos que necesitan.
- Agilidad: los recursos basados en la nube se pueden implementar y configurar rápidamente a medida que cambian los requisitos de la aplicación.
- Distribución geográfica: las aplicaciones y los datos se pueden implementar en centros de datos regionales de todo el mundo, lo que garantiza que los clientes siempre tendrán el mejor rendimiento de su región.
- Recuperación ante desastres: al usar los servicios de copia de seguridad basados en la nube, la replicación de datos y la distribución geográfica, podrá implementar las aplicaciones con la seguridad de saber que los datos están protegidos en caso de que se produzca un desastre.

## Modelos de servicio en la nube.

| Modelo informático | Descripción |
|--------------------|-------------|
| IaaS | Este modelo de servicio en la nube es el más parecido a la administración de servidores físicos. Un proveedor de servicios en la nube mantiene actualizado el hardware, pero el mantenimiento del sistema operativo y la configuración de red es responsabilidad del inquilino de nube. Por ejemplo, las máquinas virtuales de Azure son dispositivos de proceso virtuales totalmente operativos que se ejecutan en centros de datos de Microsoft. Una ventaja de este modelo de servicio en la nube es la rápida implementación de nuevos dispositivos de proceso. La configuración de una máquina virtual nueva es considerablemente más rápida que la obtención, instalación y configuración de un servidor físico.|
| PaaS  | Este modelo de servicio en la nube es un entorno de hospedaje administrado. El proveedor de servicios en la nube administra las máquinas virtuales y los recursos de red, y el inquilino de nube implementa sus aplicaciones en el entorno de hospedaje administrado. Por ejemplo, Azure App Services proporciona un entorno de hospedaje administrado en el que los desarrolladores pueden cargar sus aplicaciones web sin tener que preocuparse por el uso de los requisitos de hardware y software físicos.|
| SaaS | En este modelo de servicio en la nube, el proveedor de servicios en la nube administra todos los aspectos del entorno de la aplicación, como las máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones. El inquilino de nube solo necesita proporcionar sus datos a la aplicación administrada por el proveedor de servicios en la nube. Por ejemplo, Office 365 proporciona una versión de Office totalmente operativa que se ejecuta en la nube. Lo único que debe hacer es crear el contenido y Office 365 se encarga de todo lo demás.|


![Modelos de servicio de la nube](https://docs.microsoft.com/en-gb/learn/azure-fundamentals/intro-to-azure-fundamentals/media/iaas-paas-saas-expanded.png#lightbox)

Existen varios niveles de responsabilidad entre el proveedor y el cliente:

![Responsabilidades de proveedor y cliente](https://docs.microsoft.com/en-gb/learn/azure-fundamentals/intro-to-azure-fundamentals/media/shared-responsibility.png)

## Modelos de implementación para la informática en la nube.

| Modelo de implementación |	Descripción |
|--------------------------|----------------|
|Nube pública |	Los servicios se ofrecen a través de la red Internet pública y están disponibles para cualquiera que quiera comprarlos. Los recursos de nube como los servidores y el almacenamiento son propiedad de un proveedor de servicios en la nube de terceros, que los explota y distribuye a través de Internet.|
|Nube privada |	Los recursos informáticos son de uso exclusivo de los usuarios de una empresa u organización. Una nube privada puede estar ubicada físicamente en el centro de datos local de la organización. También la puede hospedar un proveedor de servicios de terceros.|
|Nube híbrida |	Este entorno informático combina una nube pública y una nube privada, lo que permite compartir datos y aplicaciones entre ellas.|

![Modelos de implementacion](https://docs.microsoft.com/en-gb/learn/azure-fundamentals/intro-to-azure-fundamentals/media/cloud-computing-continuum.png)

## Principales proveedores

Los 5 principales proveedores de servicios en la nube son, según la revista Forbes, Microsoft, Amazon, IBM, Salesforce y SAP. 

1. **Microsoft**: Microsoft está en el primer puesto gracias a cuatro factores principales: su oferta de servicios en las tres capas de la nube (IaaS, PaaS y SaaS); su compromiso inigualable para desarrollar y ayudar a los clientes a implementar AI, ML y Blockchain en entornos de producción innovadores; sus ingresos en la nube líderes en el mercado y la extraordinaria visión y liderazgo del CEO Satya Nadella.
 2. **Amazon**: Aunque no tiene las habilidades de software end-to-end de los demás proveedores en el Top 5, fue y sigue siendo el ejemplo modélico del movimiento del Cloud Computing. Amazon fue el primer destructor de paradigmas y creador de categorías. Amazon Web Services ofrece una experiencia de usuario sencilla y elegante además de tener con unos precios muy competitivos.
 3. **IBM**: IBM ha escalado posiciones en los últimos años tras haber superado a Salesforce.com y a SAP gracias a la transformación de su amplia gama de experiencia y tecnología de software desde el entorno real hasta la nube. IBM es también uno de los proveedores de Cloud Computing que ofrece los tres servicios: IaaS, PaaS y SaaS. Esta oferta en su servicio es una gran ventaja respecto a otros competidores dado que consigue aportar más opciones a los clientes, una integración más fluida y una mejor seguridad cibernética.
 4. **Salesforce.com**: Aunque Salesforce.com solía estar empatado con Amazon en la segunda posición, sigue siendo un importante proveedor de Cloud Computing, con gran enfoque en la innovación digital y la estrategia disruptiva. Por el momento, únicamente ofrece el servicio Saas lo que, consecuentemente, limita su número de clientes.
5. **SAP**: Tiene todo lo que los demás proveedores de esta lista desearían tener: es el proveedor de aplicaciones empresariales en todas las compañías líderes del mundo. SAP ha creado alianzas con Amazon y Google para complementar sus acuerdos con IBM y Microsoft, lo cual brinda a los clientes una mayor sensación de confianza de que SAP se puede adaptar fácilmente a nuevas situaciones. Además, SAP tiene un prometedor futuro en la nube gracias a su solución HANA. Esta tecnología de procesamiento in-memory y SAP Cloud Platform permite desarrollar nuevas aplicaciones o módulos personalizados para cualquiera de las soluciones de SAP.
El conocimiento del Cloud Computing y el dominio de los principales proveedores de esta tecnología tienen una alta demanda en el mercado laboral. El Máster en Big Data y Analytics de Three Points permite a los alumnos identificar, juntamente con negocio, cuando este tipo de soluciones pueden ayudar a la organización y gobernar una implantación dentro de la organización.


## Casos de éxito.

1. [New York Times](https://www.nytimes.com/es/)

    El conocido periódico norteamericano The New York Times necesitaba convertir 11 millones de artículos e imágenes de su archivo (de 1851 a 1980) al formato PDF. 
    El departamento de IT de la empresa estimó que el proyecto duraría unas siete semanas. Sin embargo, un desarrollador utilizando 100 instancias de Amazon EC2 logró completar el trabajo en 24 horas.
2. [General Electric](https://www.ge.com/)

    General Electric, uno de los mayores conglomerados del mundo, empezó a aplicar una estrategia de transformación digital en 2014 que revolucionó la manera de trabajar que mantenían hasta el momento. 
    En 2017, la empresa eligió a Amazon Web Services como proveedor principal para alojar más de 2000 aplicaciones y servicios en la nube. Según el propio CTO y vicepresidente de la compañía, esta elección fue una de las trasformaciones más importantes para General Electric, asegura que les ha ayudado a reorientar recursos hacia tareas de innovación que, hasta el momento, estaban ocupados diseñando y manteniendo centros de datos tradicionales.
3. [Netflix](https://www.netflix.com/mx/)

    Es difícil enumerar una lista de empresas vinculadas a la transformación digital sin nombrar a la famosa compañía de entretenimiento y distribución de contenido audiovisual en línea. 
    A pesar de tratarse de una empresa tecnológica, lo cierto es que hasta hace relativamente poco no habían apostado por los servicios en la nube. Sin embargo, dada la popularización de sus servicios y la gran cantidad de demanda de los usuarios, se han visto obligados a migrar sus centros de datos tradicionales a un entorno Cloud para poder abastecer a todos sus suscriptores. Esta migración les ha permitido expandirse de manera flexible en función de la demanda, ahorrando costes y gestionando los recursos de una manera eficiente. 








