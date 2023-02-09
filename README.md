# Enabling Ranger Plugins


#### * Login into Ranger Admin UI using your credentials. You will see following Dashboard before enabling Plugin Service

![eebf48c8-4b41-4ad7-af60-4a4aa806eb2c](https://user-images.githubusercontent.com/124764525/217804990-94b8ea1c-76d6-44f6-814a-c10803f7f344.jpg)

## 1) Setup Ranger Plugin 

#### * Ranger Service --> Click Actions > Setup Ranger Plugin Service.

![3fed3f4b-fb86-4007-824b-2839300a10bb](https://user-images.githubusercontent.com/124764525/217803375-f113386b-7127-429c-923d-48b3ca89727f.jpg)

#### * Observe Ranger Admin UI after enabling Plugin Service. Observe Yellow Highligts.

![03d3cb1a-1c11-41e9-b90d-a8508bca7101](https://user-images.githubusercontent.com/124764525/217805393-8e962256-aee1-4d64-a53e-3d1c0cbb6d35.jpg)

## 2) To enable the HDFS Ranger Authorization

#### * Click Actions --> Configurations --> Enable Ranger Authorization property

![dae342e1-2cd4-4a97-9db9-c76af143967e](https://user-images.githubusercontent.com/124764525/217801031-eb2089a5-f293-4239-9de3-80839c068656.jpg)

#### * Click -- > Restart HDFS by clicking Stale Configuration Symbol to apply new changes

![hadoop-restart-stale-service-icon](https://user-images.githubusercontent.com/124764525/217802092-a20c4961-2ab0-42fc-8807-cf897f78180d.png)

## 3) To enable the Solr Ranger Authorization

#### * Click Actions --> Configurations --> Enable Ranger Authorization property
#### * Click -- > Restart Solr by clicking Stale Configuration Symbol to apply new changes

## 4) To enable the Hive Ranger Authorization

#### * Click Actions --> Configurations --> Enable Ranger Service Property
#### * Click -- > Restart Hive by clicking Stale Configuration Symbol to apply new changes

![35475d24-e56c-4eeb-9c06-1e9fab819cc6](https://user-images.githubusercontent.com/124764525/217806539-fe1e5d01-8e5d-4b4f-911a-da3cee941db2.jpg)

#### * When u enable this property in hive you can observe following additions by clicking on stale configurations

![e5713821-cd7e-40fe-b074-cf7fd1cf6329](https://user-images.githubusercontent.com/124764525/217807024-2e043cb0-1b7b-4394-be2d-9eb640ce63f2.jpg)

## 5) Similarly you can enable Ranger Authorization for different tools that Ranger supports.

## Note : Verify Applications that are using Ranger for Authorization

#### * Ranger UI --> Audit --> Plugin Status (Observe Columns Service type & Application )

![3f3c4df1-973e-4e66-80fd-0913fc52a774](https://user-images.githubusercontent.com/124764525/217811503-7b5ea258-35b0-4426-9116-43744388aa0c.jpg)


