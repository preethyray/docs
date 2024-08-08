# Specbee starter kit


Click on `Use this template` to copy the Specbee starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```
### Live Url

https://specbeeconsultingservices.mintlify.app/introduction

### Migration content

https://specbeeconsultingservices.mintlify.app/api-reference/a-companies/get-current-company

use the following command to migrate

```
npx @mintlify/scraping@latest openapi-file rippling-support.yml -o api-reference
```




