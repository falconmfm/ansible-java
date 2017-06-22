Ansible-Java
=========

 Se trata de la primera versión de para la instalación de una versión de java.

Requisitos
------------

 Requiere que se haya ejecutado previamente el role "import" , ya que la estructura de directorio debe estar creada previamente.
 El software de jdk correspondiente a la versión debe estar en /import/temporal/subidas

Variables del Role
------------------
java_home : Indica la ruta /import/software/java1X_0X que determinará el JAVA_HOME del entorno.

Dependencias
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: import }
         - { role: java }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
