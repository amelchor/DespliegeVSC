# Deployment de Entorno de Producción

## MTIE - 501

### Inscrucciones a seguir:

### Clonar repositorio
```
git clone https://github.com/amelchor/DespliegeVSC.git
cd DespliegeVSC
```
### Para generar este codigo previamente clonar los codigos del repositorio de Peimbert

```
git clone https://github.com/jlrosasp/app-angular.git
git clone https://github.com/jlrosasp/deploy-node.git
git clone https://github.com/jlrosasp/apinetcore.git
git clone https://github.com/startbootstrap/startbootstrap-sb-admin-2
```
### Mover carpetas a directorio raíz
```
sudo mv apinetcore/ ../
sudo mv app-angular/ ../
sudo mv deploy-node/ ../
sudo mv docker-compose.yml ../
sudo mv startbootstrap-sb-admin-2/ ../
sudo mv README.md ../
```

### Crear Contenedores
```
docker-compose up --build -d
```
