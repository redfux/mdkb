---
layout: post
title: HP-Procurve - Mehrere lokale User
date: 2015-07-13 09:48:25  
tags: config,hp,switching,aaa
published: true
---


    aaa authorization group <Gruppe> 1 match-command ssh permit
    aaa authentication local-user <Username>  group <Gruppe>  password plaintext
