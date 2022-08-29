Welcome to the OpenSSL Project
==============================

[![openssl logo]][www.openssl.org]

[![github actions ci badge]][github actions ci]
[![appveyor badge]][appveyor jobs]

OpenSSL is a robust, commercial-grade, full-featured Open Source Toolkit
for the Transport Layer Security (TLS) protocol formerly known as the
Secure Sockets Layer (SSL) protocol. The protocol implementation is based
on a full-strength general purpose cryptographic library, which can also
be used stand-alone.

OpenSSL is descended from the SSLeay library developed by Eric A. Young
and Tim J. Hudson.

The official Home Page of the OpenSSL Project is [www.openssl.org].

Table of Contents
=================

 - Install

Overview
========

# OpenSSL 3.0.5 x64 for Windows

Drop the folders in binaries:

SSL on Program Files -> Common Files OpenSSL on Program Files

Then set the environment variables.

OPENSSLDIR: "C:\Program Files\Common Files\SSL"

ENGINESDIR: "C:\Program Files\OpenSSL\lib\engines-3"

MODULESDIR: "C:\Program Files\OpenSSL\lib\ossl-modules"

And add to path variables:

C:\Program Files (x86)\OpenSSL\bin

C:\Program Files\OpenSSL\lib

C:\Program Files\OpenSSL\lib\engines-3

C:\Program Files\OpenSSL\include\openssl

C:\Program Files\OpenSSL\lib\ossl-modules

C:\Program Files\Common Files\SSL

That would be all.
