## Big Bear Umbrel App Store

This repository contains the Big Bear Umbrel App Store. This app store is a community app store that is not maintained by the Umbrel team. It is maintained by BigBearTechWorld and the BigBearCommunity.

## Apps

| App Name     | Added          | Last Updated   | Updated By       | Version  |
| ------------ | -------------- | -------------- | ---------------- | -------- |
| Adguard Home | July 29th 2023 | July 29th 2023 | BigBearTechWorld | 0.107.35 |
| Chromium     | July 29th 2023 | July 29th 2023 | BigBearTechWorld | 0.0.1    |
| Cloudflared  | July 29th 2023 | July 29th 2023 | BigBearTechWorld | 0.0.1    |
| Ghost        | July 29th 2023 | July 29th 2023 | BigBearTechWorld | 5.55.2   |
| Homepage     | July 29th 2023 | July 29th 2023 | BigBearTechWorld | 0.6.23   |
| Uptime Kuma  | July 29th 2023 | July 29th 2023 | BigBearTechWorld | 1.22.1   |

## UI How to

How to add the App Store:

https://github.com/bigbeartechworld/big-bear-umbrel/assets/1289128/74a64d5e-a83f-4629-83a9-c70f11d9bb2d

## CLI How to

To add an app store:

```
sudo ~/umbrel/scripts/repo add https://github.com/bigbeartechworld/big-bear-umbrel.git
```

To update an app store:

```
sudo ~/umbrel/scripts/repo update
```

To install an app from the app store

```
sudo ~/umbrel/scripts/app install big-bear-umbrel-example-app
```

To remove an app store:

```
sudo ~/umbrel/scripts/repo remove https://github.com/bigbeartechworld/big-bear-umbrel.git
```
