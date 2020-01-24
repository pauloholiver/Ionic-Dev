# Instalando Ionic e Cordova
   
   npm install -g ionic
   npm install -g cordova


# Build Android

    ionic build --watch --platform=android --engine=cordova

# Live Reload

    ionic serve 
    ionic cordova run android -l --device
    ionic cordova run ios -l --external --device