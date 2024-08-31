# GraphQL
This repository is for demo graphql as golang

우리는 datapool이란 namespace가 있고 내부에 datapool 속성을 가지는 여러 서비스들이 있었다.
이 서비스들과 Front단에 중간 다리 역할을 하는 Gateway라는 서비스가 있었다.
Gateway는 서비스에 대한 단일 호출 지원 뿐만 아니라, 여러 서비스의 결과를 Aggregation 하여 도출하는 기능도 포함 하고 있었다.
이 Gateway 서비스를 GraphQL을 사용하여 Migration을 해보려고 한다.