---
ext: .md
position: 2
title: OpenTelemetry
---
# OpenTelemetry
- [Configure Azure Monitor Telemetry](https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-configuration?tabs=aspnetcore)

- [Download and install Podman with winget](https://winget.run/pkg/RedHat/Podman)
- [Standalone .NET Aspire dashboard](https://learn.microsoft.com/en-us/dotnet/aspire/fundamentals/dashboard/standalone?tabs=bash)

<div class="mermaid">
flowchart LR
subgraph Azure
subgraph am[Azure Monitor]
subgraph ai[Application Insights]
ai-otel-dev
end
subgraph la[Log Analytics]
la-otel-dev
end
end
end
Web-->ACS{AI<br>environment<br>variable ?}
ACS-->|yes|ai-otel-dev-->la-otel-dev
ACS-->|no|d[Standalone .NET Aspire dashboard]
</div>
