# How do I configure the adapter to work?

- [How do I configure the adapter to work?](#how-do-I-configure-the-adapter-to-work?)
  - [PrivateToken](#privatetoken)
  - [ProjectId](#projectid)
  - [ConfigurationId](#configurationid)

## PrivateToken

___

Getting API secret key. To do that:

1. Go to the profile settings  
![](/images/profile_menu.png)
2. Open the security tab and copy the API secret key
![](/images/private_token.png)

## ProjectId

___

Getting project ID. To do that:

1. Open DevTools (button F12) > Network  
![](/images/dev_tools.png)
2. Go to the project https://{DOMAIN}/projects/{PROJECT_GLOBAL_ID}/tests
3. GET-request project, Preview tab, copy ID field
![](/images/get-request-project.png)

## ConfigurationId

___

Getting configuration ID. To do that:

1. Open DevTools (button F12) > Network  
![](/images/dev_tools.png)
2. Go to the project https://{DOMAIN}/projects/{PROJECT_GLOBAL_ID}/tests
3. GET-request configurations, Preview tab, copy id field
![](/images/get-request-configurations.png)
