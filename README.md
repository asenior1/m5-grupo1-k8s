# Modulo 5 - Grupo 1 - K8s

### Aplicar Cambios

En el directorio principal del repositorio se debe ejecutar:

`kubectl apply -f grupo1.yml`

### Validar Cambios

Ejecutar:

`kubectl get po -n grupo1`

Se deben mostrar los pods que se encuentran ejecutandose.

### Configurar Ingress

Ejecutar:

`kubectl get ingress -n grupo1`

La direccion IP que se muestra en ADDRESS se debe configurar (IP_ADDRESS).
Agregar esta linea al final del archivo /etc/hosts (Cambiando IP_ADDRESS por el valor correspondiente):

`IP_ADDRESS minikube-grupo1.com`


### Probar Ingress

Abrir en un navegador `minikube-grupo1.com`