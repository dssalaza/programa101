# Máquinas Virtuales \(VM\)

El desarrollo de software usando máquinas virtuales \(VM's\) permite aislar las dependencias de las bibliotecas de software y limitar los recursos necesarios para que un sistema funcione correctamente. Lo más importante es que ha simplificado la portabilidad y la escalabilidad, sin embargo para funcionar adecuadamente necesitan ser operadas por un hipervisor sobre el cual se instala un sistema operativo. El uso de múltiples controladores y el hecho de compartir recursos de hardware con la computadora host permite ejecutar varias VM en un servidor. las VM's se utilizan ampliamente en las arquitecturas de Infraestructura como Servicio \(IaaS\) por las facilidades que ofrecen para administrar recursos, estas juegan un papel vital en la computación en nube, grandes empresas de informática como Google, Microsoft o Amazon han construido diferentes tipos de servicios en la nube ofreciendo VM's personalizadas. Estos tipos de servicios ofrecen componentes de hardware ajustables, que se configuran en función de las necesidades.

A continuación vamos a listar los beneficios de las VM's:

* Todos los recursos del sistema operativo disponibles para las aplicaciones 
* Instrumentos de gestión establecidos 
* Herramientas de seguridad establecidas 
* Controles de seguridad más conocidos

Así mismo actualmente hay varios proveedores de VM's entre los cuales tenemos:\

* [VMware vSphere](https://www.vmware.com/products/vsphere.html)
* [VirtualBox](https://www.virtualbox.org/)
* [Xen](https://www.xenproject.org/)
* [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/)
* [KVM](https://www.linux-kvm.org/page/Main_Page)

### Contenedores

La tecnología de contenedores es una alternativa a las VM's; mejora el uso de los recursos de hardware y permite compartir el consumo de CPU, RAM y la transferencia de datos a través de la red. Los mismos recursos de hardware pueden ser utilizados por varias aplicaciones de software. Esto abre la posibilidad de ampliar el concepto de Infraestructura como Servicio \(IaaS\) introduciendo los Contenedores como Servicio \(CaaS\). La tecnología de contenedores ha crecido rápidamente debido a sus características que permiten ejecutar aún más aplicaciones de software en el mismo hardware que usando VM.

![](../.gitbook/assets/comparacion-vm-vs-contenedores.png)

A continuación se listan los principales beneficios de usar contenedores

* Reducción de los recursos de gestión de TI
* Reducción del tamaño de los snapshots
* Aplicaciones que se pueden ejecutar más rápido
* Actualizaciones de seguridad reducidas y simplificadas
* Menos código para transferir, migrar, subir cargas de trabajo

Así mismo en contenerización hay varios proveedores como:

* [Linux Containers](https://linuxcontainers.org/)
  * [LXC](https://linuxcontainers.org/lxc/)
  * [LXD](https://linuxcontainers.org/lxd/introduction/)
  * [CGManager](https://linuxcontainers.org/cgmanager/introduction/)
* [Docker](https://www.docker.com/)
* [Windows Server Containers](https://docs.microsoft.com/en-us/virtualization/windowscontainers/about/)



