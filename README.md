# magento-react-native
React Native mobile app for Magento 2.x

<img src="https://github.com/troublediehard/magento-react-native/blob/master/android/app/src/main/ic_launcher-web.png" alt="Logo" width="250px"/>

# Setup
**Magento Admin**
* System > Intergrations > Add New Intergration
* Fill Name filed and password
* API > Resource Access select all (in production you can select only resources you really need)
* Save
* Acitvate your Integration

**React Native Project setup**
* Go to repository dir
* Run npm install
* Then react-native link react-native-vector-icons
* copy src/config/magento-sample.js to src/config/magento.js
* set Magento base url to url param in magento.js
* set Access Token from Integration you created to access_token param in magento.js
* react-native run-ios (for iOS) and react-native run-android (for Android)

# Demo
![Demo](docs/gifs/demo.gif)

## You can contact me

I open to any discussion. I have [Slack](https://magento-react-native.slack.com/) workspace so ping me via email if you want to join. 

troublesohard@gmail.com

[upwork](https://www.upwork.com/o/profiles/users/_~019a1afcd3f56e9469/)

[linkedin](https://www.linkedin.com/in/dmitry-portenko-712ab84a/)

## License
[MIT License](LICENSE.md) Copyright (c) 2017-2018 [Dmytro Portenko](https://www.linkedin.com/in/dmitry-portenko-712ab84a/).
