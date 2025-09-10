---
position: 1
title: Welcome
---
# {{ page.title }}
- [`dotnet user-secrets`](https://learn.microsoft.com/en-us/aspnet/core/security/app-secrets)
- [`dotnet user-jwts`](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/jwt-authn)
- [Playwright](https://playwright.dev/)
- [Runner Images](https://github.com/actions/runner-images/tree/main?tab=readme-ov-file#readme)
- [`psql`](https://www.postgresql.org/docs/current/app-psql.html)
- [Terraform](https://developer.hashicorp.com/terraform)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Rancher Desktop by SUSE](https://rancherdesktop.io/)
index.md
<hr>
patrice-sc | GitHub Pages
<hr>
{% assign sorted_pages = site.pages %}
{% for page in sorted_pages %}
  <a href="{{ page.url }}">{{ page.title }} Test</a>
{% endfor %}
