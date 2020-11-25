# Okta React Native + Browser Sign In Example

###Running This Example for iOS

1. install dependencies: 
```npm ci```

2. Install dependecies for iOS.
```cd ios```
```pod install```

3. Now start the app server:
```npm start```

Or launch iOS Simulator
```npm run ios```

## Methods
In this sample application, once the user logs in, there will be three methods that each shows a different way to get user info. 

### Get User From ID Token ###
This method calls `getUserFromIdToken()` to retrieve user info from decoding the ID Token claims.

### Get User From Request ###
This method calls `getUser()` to retrieve user info by passing in the access token, and making a request to the user info endpoint. It is done on the native modules. 

### Get User From Access Token ###
This method shows you how to use the access token from `getAccessToken()` to exchange user information. It shows how to make a fetch request to the user info endpoint with access token as the header.