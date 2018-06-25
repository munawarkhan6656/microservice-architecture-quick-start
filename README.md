# microservice-architecture-quick-start
- C# 언어와 ASP.NET Core 환경을 이용하여 마이크로서비스 아키텍처를 구축하는 방법을 보여줍니다.
- (Demonstrates how to build a micro services architecture using the C # language and the ASP.NET Core environment.)


## Requirements

- Install [Docker](https://docs.docker.com/install/)
- Install [.NET Core 2.1](https://www.microsoft.com/net/download) 


## Limits
1. Used In-Memory Database


## Infrastructure
- [ ] [Ocelot](https://github.com/ThreeMammals/Ocelot) (Api Gateway)
- [x] NLog
- [x] Swagger Integration
- [x] Entity Framework Core DbContext
- [x] TraceId about Request
- [ ] Exception Handling
- [x] Guard
- [ ] AutoMapper
- [x] Data Protection
- [x] Polly
- [ ] Health Check

Domain Driven Development
- [x] Aggregate Root
- [x] ValueObject
- [x] CQRS
- [x] Event Sourcing
- [ ] Unit Of Work


## Run

#### Download Source Code

```
git clone https://github.com/powerumc/microservice-architecture-quick-start
```

#### Run Commands

##### 1. Move `provisioning` directory.

```
cd provisioning
```

##### 2. Run docker-compose

```
docker-compose up -d
```