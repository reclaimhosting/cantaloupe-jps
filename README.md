# Cantaloupe IIIF Image Server for Reclaim Cloud
Cantaloupe is an open-source IIIF-compliant dynamic image server for on-demand generation of derivatives of high-resolution source images.
## Deploy to Reclaim Cloud
[Click here to deploy to Reclaim Cloud](https://app.my.reclaim.cloud/?app=cantaloupe)

## Installation Instructions
You can find Cantaloupe by clicking Marketplace and navigating to the Education category or searching by name.

![Screen Shot 2020-07-12 at 9.13.45 AM|480x144](https://community.reclaimhosting.com/uploads/default/original/2X/5/563d14d24d6dae4e3797f8895cdb80fa958a6474.png) 

![Screen Shot 2020-07-25 at 7.26.08 PM|690x337](https://community.reclaimhosting.com/uploads/default/original/2X/1/1102261965bce0de1ee83de25c6373f7e2aab08d.png) 

Installing is as easy as setting an environment name and region for the install. SSL will be provisioned automatically for the environment and your install will be up and running after several minutes. The installer dialog will provide and administrative URL and login credentials once setup is complete.

![Screen Shot 2020-07-25 at 7.26.37 PM|690x354](https://community.reclaimhosting.com/uploads/default/original/2X/d/d96fafb95214a0994263be0164b0e4a6de4e7e29.png) 

![Screen Shot 2020-07-25 at 7.26.45 PM|690x232](https://community.reclaimhosting.com/uploads/default/original/2X/3/366dd9f47bab1ec88c57fba9c866d2de474d33ac.png) 

![Screen Shot 2020-07-25 at 7.30.43 PM|690x288](https://community.reclaimhosting.com/uploads/default/original/2X/0/049ac1544b75f14203863fc93f0aaa9fe7838997.png) 

You can confirm the image server is online by accessing the homepage as well as the administrative area with the provided login.

![Screen Shot 2020-07-25 at 7.30.55 PM|690x457](https://community.reclaimhosting.com/uploads/default/original/2X/2/23fbb5e18784e5d8624bd106ca2d461df1dfb2a5.jpeg) 

![Screen Shot 2020-07-25 at 7.31.12 PM|690x446](https://community.reclaimhosting.com/uploads/default/original/2X/3/3b4a76e099204fe18ce1d34a93a85ba725521134.jpeg) 

To start serving images, a shortcut to the appropriate directory is available from the Config section under **IMAGES**

![Screen Shot 2020-07-25 at 7.32.49 PM|690x274](https://community.reclaimhosting.com/uploads/default/original/2X/e/ecb060e9f1db6ae773e07f2607eddb3da3ef5927.png) 

![Screen Shot 2020-07-25 at 7.33.01 PM|690x416](https://community.reclaimhosting.com/uploads/default/original/2X/4/4da391b3158ca4611a2361eb8133caa9cf59064c.png) 

You can also upload images via [SFTP](https://docs.jelastic.com/ssh-protocols/) to the `/home/jelastic/images` directory. To learn more about IIIF visit https://iiif.io and read about some of the various viewers and tools to work with IIIF like Mirador and OpenSeaDragon at https://iiif.io/apps-demos/#awesome-iiif.