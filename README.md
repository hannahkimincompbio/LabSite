# Lab Website

## Contributing
To modify the content just edit one of the three JSON files in the `src/data` directory. Layout or styling modifications can be made via a pull request or by reaching out to Michael.

## Development

### Installation

```
git clone https://github.com/veg/LabSite
cd LabSite
yarn
```

### Dev Server

Start the development server:

```
yarn start
```

## Deployment
Make/pull appropriate changes, then:

```
yarn run build
```

To serve (only necessary if `pm2` is not already provisioning this process):
```
supervisor server.js
```
