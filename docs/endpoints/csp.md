---
layout: docs-default
---

#CSP Endpoint

[CSP](../advanced/csp.html) allows for a reprting endpoint to be configured. IdentityServer provides a endpoint to record CSP errors that the browser reports. These CSP errors will be raised as [events](../configuration/events.html) in the eventing system.

The CSP reporting feature can disabled by setting the `EnableCspReportEndpoint` property to `false` on the `EndpointOptions` which is a property of the [`IdentityServerOptions`](../configuration/identityServerOptions.html).
