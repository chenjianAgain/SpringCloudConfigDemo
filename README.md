# SpringCloudConfigDemo

server:
  port: 8888
management:
  security:
    enabled: false
spring:
  cloud:
    config:
      server:
        git:
          uri: https://github.com/chenjianAgain/SpringCloudConfigDemo
#          searchPaths:
