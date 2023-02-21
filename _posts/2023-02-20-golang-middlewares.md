---
title: Golang Middlewares
categories: [golang]
tags: [golang,backend,middleware,rest,api]
---

# Middlewares In Golang

## About & Context & Examples & 
In the simplest terms: Middlewares are the intermediators or a layer of 
abstraction between the sender and the receiver of any request.
> Middleware is software that enables one or more kinds of communication or 
> connectivity between two or more applications or application components in a distributed network.
 
For example: In real life, an interpreter who translates source text/speech from
one language to another is a middle-man. In software world, we'd call it as a 
middleware.

## Types of middlewares and where it is being used
Depending upon where we place the code for executing middleware code, 
middleware are of two 

## Endpoints vs Middleware

| Endpoint                    | Middleware                                                            |
|-----------------------------|-----------------------------------------------------------------------|
| Can be called by the users  | Cannot be called by the users directly                                |
| Typically used by end-users | User by developers to intercept requests and get/add some information |

## Benefits of using middleware
1. core business logic is separated from other things.
2. grouping more than one endpoint
