# Boilerplate for Vue Storefront 2 eCommerce integration

This is a template, to use it you must rename the project changing the `{YOUR INTEGRATION NAME}` to the name of the integration you are developing. The name must be in lowercase and without any special characters.

```sh
grep -rl 'bhisma' ./ | xargs sed -i '' 's/bhisma/{YOUR INTEGRATION NAME}/g'
```

------

<div align="center">
<img src="https://blog.vuestorefront.io/wp-content/uploads/2020/01/1QU9F6hQlFyHsJIbsdmt6FA.png" height="80px"/>  
</div>

## Vue Storefront 2 integration with bhisma

To learn how to build your integration, see our [Integration guide](https://docs.vuestorefront.io/v2/integrate/integration-guide.html).

------

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## How to start if you want to try out the integration

```
yarn global add @vue-storefront/cli
```
```
vsf init <project_name> && cd <project_name> && yarn && yarn dev
```

## How to start if you want to contribute?

Want to contribute? Ping us on `bhisma` channel on [our Discord](https://discord.vuestorefront.io)!

### Requirements:
- NodeJS v14 or later

### Steps
1. Fork the repo
2. Clone your fork of the repo
    ```
    example:
    git clone https://github.com/vuestorefront/bhisma.git
    cd bhisma
    ```
3. Run `yarn` to install dependencies
4. Build dependencies `yarn build:api-client && yarn build:composables`
5. Run `yarn dev:theme` to run theme. You can find other commands in `package.json`

- If you need HMR on Api Client/Composables run `yarn dev:api-client` or `yarn dev:composables` on a separate terminal window.

## Resources

- [Vue Storefront Documentation](https://docs.vuestorefront.io/v2/)
- [bhisma integration Documentation](https://docs.vuestorefront.io/bhisma)
- [Community Chat](https://discord.vuestorefront.io)

## Support

If you have any questions about this integration we will be happy to answer them on `bhisma` channel on [our Discord](discord.vuestorefront.io).

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
