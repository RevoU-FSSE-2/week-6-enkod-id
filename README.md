# How to download docker in windows
> "Docker" is a software platform that allows you to develop, test, and run applications in an isolated environment called "containers." In this context, "containers" refer to standardized software units that package all the elements needed by software, including code, runtime, libraries, and other dependencies. This enables applications to run consistently in various environments, both on development computers and in production environments


![](header.png)

## Installation

Search "docker" in google.com <br>
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/1eafd538-9c07-402f-9262-dde2d6ed8676" width="800"/>



Download and save to directory 
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/83f296f7-821e-4ee7-bc62-95b230b116bb" width="800"/>



<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/ffb082ed-e752-4f3f-918d-cf1501a1fbf8" width="800"/>



Click & install <br>
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/453cf184-87ce-4e5c-b219-78b0b3af729a" width="800"/>



<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/4853f6ff-db21-4184-b68a-c3f01aeee507" width="800"/>



<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/e8b5afcd-9c32-4543-ad92-3e696397106f" width="800"/>



```sh
docker --version
```



Done<br>
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/77b60efa-d311-4dd1-91ec-fade6c9f8b9a" width="800"/>

## Download image nodejs in docker

```sh
docker pull node:18.17.0-alpine
```
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/d1c599ca-3ae3-4b07-9725-1c3f15139038" width="800"/>



## Download Nodejs Hello World App(app.js)
<ul>
  <li>Download Download app.js from https://gist.github.com/berdoezt/e51718982926f0caa3fcd8ed45111430 and move new folder</li>
  <li>Create file with name Dockerfile, edit file with this code, and save at same folder with app.js<br>
    <img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/97e9874f-5f4b-4239-8d98-b7e9f5af5aaa"/><br>
  <img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/210a8e62-8aa2-4a51-a176-064eb78f41ef"/>


  </li>
</ul>
```sh
$ docker build -t nodejs_hello-world .

```
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/2e6b1b92-0cf0-4dd2-8219-246213e544af"/>

```sh
$ docker images
```
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/4eb39c66-f755-4ccb-8dc8-5f114887e20e"/>
<br>
<img src="https://github.com/RevoU-FSSE-2/week-6-enkod-id/assets/18107640/5671ff78-8183-4adf-bb93-491c92fa8ea9"/>

congratz
