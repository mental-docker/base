# Base image
Used ubuntu latest ()16.04, xenial-20170710)

## Build

  <pre><code>
  docker build -t mental/base .
  </code></pre>
  
## Push docker

``` 
docker login
```
Result
```
Username (coskundeniz1989): coskundeniz1989
Password: 
Login Succeeded
```


``` 
docker push mental/base
```
Result

```
The push refers to a repository [docker.io/mental/base]
26b126eb8632: Mounted from library/ubuntu 
220d34b5f6c9: Mounted from library/ubuntu 
8a5132998025: Mounted from library/ubuntu 
aca233ed29c3: Mounted from library/ubuntu 
e5d2f035d7a4: Mounted from library/ubuntu 
latest: digest: sha256:af8cd9ae1c85466b8e77005231850c5f2ae949e8d53c866c7bb393edfdbddabe size: 1357
```