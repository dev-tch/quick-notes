## local config to call the rephrase end point for public rfp

- project : rise-source-manager

- file: CvMatcherRestServiceImpl.java 

```
this.authUrl = "https://source-development-hotel.argocd.littlebig.team/internal/api/login/v1/oauth/token";
this.clientId = "vSgAMAuVabbXnDQARzIxz0SQmIk6jbA0";
this.clientSecret = "VRYG3yBbYhS4hBbdrOts23kAcsG5ZygpiXpZtvCarBLxonpnjmSkkujmiwZCJDpv";

```

### comment these lines

```
//authenticate();
//headers.setBearerAuth(this.authToken.getToken());

```
