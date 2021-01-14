---
author: justin
title: API Updates
description: A big overhaul to the SportKeeper API which includes the addition of new methods and endpoints.
featured_image: /assets/img/sections/december-update-photo.jpg
permalink: /posts/11-api-updates
date: 2019-10-16
---

I've pushed out some changes that harden the security of the API, and added several new endpoints and methods in the process. In the previous version of our API, all you needed was an API token, found in your account dashboard. While this token could be rolled (switched out) at the click of a button, it remained a not so secure method of interacting with the SportKeeper API. 

In the new version, you now log in to the SportKeeper API with your email and password, at which point you'll receive an auth token that you'll use to make future requests to the API with.

In addition, I've added create, update, and destroy methods to each of the endpoints in the API. With these updates, it makes the SportKeeper API a fully functional API that you can interact with completely independent of the web interface. Subsequently, this is also the type of functionality required to make such things as iOS and Android apps a future reality.

Check out the [API documentation](https://docs.sport-keeper.com/api-reference/overview) for further details.