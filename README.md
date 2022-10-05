# home-assistant-ssl-from-asus-router
## About
This add-on helps transfer the SSL sertificate that Asus Stock Routers creates along with it's DDNS feature into Homeassitant.

## Configurable Options
| key | Type | Description | Required/Optional 
| --- | --- | --- | --- 
| routerUser | String | The user name to SSH with router | Required
| routerIp | String | The IP Address to the router | Required
| routerSshPort | String | The port for SSH into the router | Required
| rsaPrivateKeyPath | String | The path relative to `config` folder that points to the RSA private key need to establish the SSH connection | Required
| keyFilePathOnRouter | String | The key file path on the router | Required
| certFilePathOnRouter | String | The cert file path on the router | Required

## Attribution
This is a fork of the following project:
* <a href="https://github.com/s92025592025/home-assistant-ssl-from-asus-router" title="original project">home-assistant-ssl-from-asus-router by s92025592025
(Flying_Apple_Pie)</a>

icon.png is made thanks to the following:
* <a href="https://www.flaticon.com/free-icons/pickup-truck" title="pickup-truck icons">Pickup-truck icons created by Freepik - Flaticon</a>
* <a href="https://www.flaticon.com/free-icons/certificate" title="certificate icons">Certificate icons created by Smashicons - Flaticon</a>
