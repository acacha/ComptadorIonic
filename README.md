- Aplicació: https://acacha.github.io/comptador-ionic
- Repositori Github pages: https://github.com/acacha/comptador-ionic

https://user-images.githubusercontent.com/4015406/140897122-ba0798af-0c4c-40df-88f8-6c1c2575e30e.mp4

# Screencasts

https://tubeme.acacha.org/ionic

Els tres primers vídeos són d'introducció a Javascript Modern, NodeJs i npm, Paquets/Bundles Javascript i eines modernes o paquet Bundlers com ViteJs, Webpack o Laravel Mix.

# Autor

- Github: https://github.com/acacha/
- Sergi Tur Badenas: https://acacha.github.io
- Instagram: https://instagram.com/acacha_dev
- Github: https://github.com/acacha

![image](https://user-images.githubusercontent.com/4015406/140644527-e186bf90-e556-4970-98ed-3f00c5f1af11.png)


# Codi Font dels alumnes

- Goncear, Tudor | https://github.com/tgoncear/ComptadorIonic
- Tur Badenas, Sergi  | https://github.com/acacha/ComptadorIonic
- Pont Lopez, David | Palanka777 | https://github.com/Palanka777/ComptadorIonic.git

# Projecte en explotació dels alumnes

- Goncear, Tudor | https://comptador-ionic-lack.onrender.com/home
- Tur Badenas, Sergi  | https://comptador-ionic.onrender.com/
- Pont Lopez, David | Palanka777 | https://pxlnkx.github.io/comptador-ionic

## Instal·lació

https://www.youtube.com/watch?v=W7_nsDeDvvw&list=PLyasg1A0hpk1Ew0daOLwgkt02EcZwXrEY&index=4&t=918s

Continguts:
- Documentació: https://ionicframework.com/
- Instal·lació de ionic cli. Eines de línia de comandes per a crear i gestionar projectes Ionic
- Crear-se un compte a Ionic fent un login amb Github mateix
- Creació d'un primer projecte ionic amb ionic cli

$ ionic start

I seguiu el wizard segons els passos indicats al videos

Ionic ja no és hibrid sinó que amb Capacitor permet accedir a serveis natius en un mòbil i a més Ionic genera codi natiu.

- Executar i provar l'aplicació ionic web
- Instal·lació android capacitor
- Afegir la plataforma Android
- Estructura d'una aplicació Ionic


Comandes:

```
ionic --version
ionic start
ionic serve
ionic capacitor add
ionic capacitor copy android
ionic capacitor run android
ionic build
ionic build android
ionic cordova build android
ionic capacitor run android -l --host=192.168.0.129

Exemple de configuració de l'entorn:

```bash
cat ~/.zshrc
export PATH=${PATH}:/home/sergi/Android/Sdk/platform-tools


export ANDROID_SDK_ROOT=/home/sergi/Android/Sdk
export PATH=$PATH:$ANDROID_SDK_ROOT/tools/bin
export PATH=$PATH:$ANDROID_SDK_ROOT/platform-tools
export PATH=$PATH:$ANDROID_SDK_ROOT/emulator

export CAPACITOR_ANDROID_STUDIO_PATH=/home/sergi/phpstorm/studio

export JAVA_HOME=/home/sergi/.local/share/JetBrains/Toolbox/apps/AndroidStudio/ch-0/203.7678000/jre/
```
