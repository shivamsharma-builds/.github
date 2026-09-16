---
layout: post
title: "DMI Week 00 — Internet and Networking"
description: "What really happens when you type a URL into your browser."
permalink: /blogs/dmi-week-00-internet-and-networking/
date: 2026-09-16
---

# What happens when you type a URL into your browser?

When you enter a URL such as `https://example.com`, several networking and web technologies work together before the requested page appears.

## 1. DNS resolution

The browser needs to translate the domain name into an IP address. DNS performs this name-resolution process, using caches and DNS servers.

## 2. Establishing a connection

For HTTPS, the browser establishes a secure connection to the server. Modern websites commonly use TCP with TLS or QUIC/HTTP/3 depending on the server and client.

## 3. HTTP request

The browser sends an HTTP request containing information such as the method, path, headers, and sometimes a request body.

## 4. Server response

The server returns an HTTP response containing a status code, headers, and usually HTML or another resource.

## 5. Rendering

The browser parses the HTML, discovers CSS, JavaScript, images, fonts, and other resources, then builds and renders the page.

## DevOps takeaway

Understanding DNS, IP addressing, HTTP/HTTPS, TLS, routing, ports, and client-server communication makes troubleshooting web applications and infrastructure much easier.

This article is part of my **DevOps Micro Internship** learning journey.
