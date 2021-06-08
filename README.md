# Sign in with Apple Demo


## Setting up WSO2 Identity Server

1. Change the hostname
Refer: https://is.docs.wso2.com/en/latest/setup/changing-the-hostname/#changing-the-hostname

2. Enable CORS for Apple endpoints (To Allow form_post response mode)
Refer: https://is.docs.wso2.com/en/latest/learn/cors/#configuring-cors-during-deployment

Sample [deployment.toml](https://github.com/mefarazath/identityIn15-SignInWithApple/blob/main/deployment.toml) file

**Step by step guide:** https://medium.com/identity-beyond-borders/sign-in-with-apple-using-wso2-identity-server-893cd47f3f5c 



## Sign in with Apple Dev Documentation

- [Authorization Endpoint](https://developer.apple.com/documentation/sign_in_with_apple/sign_in_with_apple_js/incorporating_sign_in_with_apple_into_other_platforms)
- [Token Endpoint](https://developer.apple.com/documentation/sign_in_with_apple/generate_and_validate_tokens)
- [Creating Client Secret](https://developer.apple.com/documentation/sign_in_with_apple/generate_and_validate_tokens#discussion)
