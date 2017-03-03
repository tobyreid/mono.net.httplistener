Mono.Net.HttpListener
==================

**This fork of HttpListener is compatible with the first release of .NET 2.0 available for Window 2000.  The consequence is that SSL is not supported / commented out**

A fully managed HttpListener implementation extracted from Mono

It's not as complete or capable as the .net implementation of System.Net.HttpListener relying on IIS, but it doesn't require Administrator rights to listen on all interfaces, making it perfect to serve http content for testing.
