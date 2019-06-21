# Open source React Native mobile app for Magento 2
<img src="https://github.com/troublediehard/magento-react-native/blob/master/android/app/src/main/ic_launcher-web.png" alt="Logo" width="250px"/>

```diff
+ If you are Magento store owner and you want free mobile app for it. 
+ Drop me a line I have a proposition for you. You can find my contacts below.
```

# Setup
**Magento Admin**
* System > Intergrations > Add New Intergration
* Fill Name filed and password
* API > Resource Access select all (in production you can select only resources you really need)
* Save
* Acitvate your Integration  
More details in docs https://devdocs.magento.com/guides/v2.3/get-started/authentication/gs-authentication-token.html

**React Native Project setup**
* Go to repository dir
* Run `npm install`
* copy `src/config/magento-sample.js` to `src/config/magento.js`
* set Magento base url to url param in `magento.js`
* set Access Token from Integration you created to `access_token` param in `magento.js`
* `react-native run-ios` (for iOS) and `react-native run-android` (for Android)

**Home screen setup**
* Go to Magento Admin
* Content > Blocks > Add New Block
* Put your config inside `Content` section ([config sample](src/config/cms_block_config.json))
* save your block and put it's `ID` in `src/config/magento.js` to `home_cms_block_id` param

# Demo
![Demo](docs/gifs/demo.gif)

## Alternative projects
MageCart: Magento 2 React Native project - https://github.com/alexakasanjeev/magento_react_native


## You can contact me

I open to any discussion. I have [Slack](https://join.slack.com/t/magento-react-native/shared_invite/enQtNjE3ODY0MDUxOTQyLWU4MzViODdmMTg0NTQ5MGVjYjM1ODI4ZTgxZDJhYzFlNjMyOTI2MmZiZDIxNDBmZDJjNTQ5MGIyYmY4NzMxMzE) workspace so ping me via email if you want to join. 

troublesohard@gmail.com

[upwork](https://www.upwork.com/o/profiles/users/_~019a1afcd3f56e9469/)

[linkedin](https://www.linkedin.com/in/dmitry-portenko-712ab84a/)

## License
[MIT License](LICENSE.md) Copyright (c) 2017-2019 [Dmytro Portenko](https://www.linkedin.com/in/dmitry-portenko-712ab84a/).
