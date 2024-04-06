<h1 align="center">Wizarr</h1>
<h3 align="center">The Free Media Invitation System</h3>

---

<p align="center">
<img src="https://raw.githubusercontent.com/Wizarrrr/wizarr/master/apps/wizarr-frontend/src/assets/img/wizard.png" height="200">
<br/>
<br/>
<a href="https://github.com/wizarrrr/wizarr">
<img alt="GPL 2.0 License" src="https://img.shields.io/github/license/wizarrrr/wizarr.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/wizarrrr/wizarr.svg"/>
</a>
<a href="https://hosted.weblate.org/engage/wizarr/">
<img src="https://hosted.weblate.org/widgets/wizarr/-/app/svg-badge.svg" />
</a>
<a href="https://opencollective.com/wizarr">
<img alt="Donate" src="https://img.shields.io/opencollective/all/wizarr.svg?label=backers"/>
</a>
<a href="https://features.wizarr.dev">
<img alt="Submit Feature Requests" src="https://img.shields.io/badge/vote_now-features?label=features"/>
</a>
<a href="https://discord.gg/XXCz7aM3ak">
<img alt="Chat on Discord" src="https://img.shields.io/discord/1020742926856372224"/>
</a>
<a href="https://www.reddit.com/r/wizarr">
<img alt="Join our Subreddit" src="https://img.shields.io/badge/reddit-r%2Fwizarr-%23FF5700.svg"/>
</a>
<a href="https://github.com/Wizarrrr/wizarr/issues">
<img alt="Github Issue" src="https://img.shields.io/github/issues/wizarrrr/wizarr"/>
</a>
<a href="https://features.wizarr.dev">
<img alt="Submit Feature Requests" src="https://img.shields.io/badge/fider-vote%20on%20features-success.svg"/>
</a>
<a href="https://github.com/Wizarrrr/wizarr/actions/workflows/release.yml">
<img alt="Github Build" src="https://img.shields.io/github/actions/workflow/status/wizarrrr/wizarr/release.yml"/>
</a>
</p>

---

# WIZARR NOTICE

Wizzar is back in development after the main developer Ash went MIA. Stay tuned for `4.0.0-beta.1` which will be the first release of the new development team. We are working hard to make Wizarr even better than before.

---

## What is Wizarr?

Wizarr is a automatic user invitation system for Plex and Jellyfin. Create a unique link and share it to a user and they will be invited to your Media Server after they complete there signup proccess! They can even be guided to download the clients and read instructions on how to use your media software!

## What's the difference between V3 and V4?

V3 is the current stable version of Wizarr, it is a fully functional system that allows you to invite users to your media server. V4 is the next version of Wizarr that is currently in development (curently the exact same as `3.5.1-beta.7`). There's not much diffrence between the two versions, V4 will involve a refactoring of the codebase and a few new features. V4 will be the first version of Wizarr that is developed by the new development team.

## Major Features Include

-   Automatic Invitation to your Media Server (Plex, Jellyfin)
-   Support for Passkey authentication for Admin Users
-   Create multiple invitations with different configurations
-   Make invitations and users expire after a certain amount of time
-   Automatically add users to your Request System (Ombi, Jellyseerr, Overseerr)
-   Add users to your Discord Server
-   Create a custom HTML page
-   Multi-Language Support
-   Scheduled Tasks to keep Wizarr updated with your Media Server
-   Live logs directly from the Wizarr Web UI
-   Multiple Admin Users with different permissions
-   Notification System
-   API for Developers with Swagger UI
-   Light and Dark Mode Support
-   Session Management for Admin Users

## Whats to come

-   Added API Endpoints
-   Multi-Server Support
-   Mass Emailing to Client Users
-   OAuth Support with custom providers
-   Use your own Database
-   2FA Support for Admin Users
-   Built in Update System
-   Full Wizard Customization with Drag and Drop Template Editor
-   Jellyfin and Plex user permissions management tool
-   Invite Request System for users to request invite
-   and much more!

## Getting Started

This version is the exact same as `3.5.1-beta.7` for now but we will be updating the codebase soon. You can install Wizarr by following the instructions below.

```
docker run -d \
    --name wizarr \
    -p 5690:5690 \
    -v ./wizarr/database:/data/database \
    ghcr.io/wizarrrr/wizarr:latest
```

```
---
version: "3.5"
services:
  wizarr:
    container_name: wizarr
    image: ghcr.io/wizarrrr/wizarr:latest
    ports:
      - 5690:5690
    volumes:
      - ./wizarr/database:/data/database
```

## Documentation

Any issues we welcome you to come onto our [Discord](https://discord.gg/XXCz7aM3ak) and ask for a member of staff, we would be happy to help.

If you want to help contribute to Wizarr by building V4's documentation we would really appreciate it, again join the [Discord](https://discord.gg/XXCz7aM3ak) and we can get you started.

~~Check out our documentation for instructions on how to install and run Wizarr!
[View Documentation](https://github.com/Wizarrrr/wizarr/blob/master/docs/setup/README.md)~~

<a href="https://discord.gg/XXCz7aM3ak">
<img alt="Chat on Discord" src="https://img.shields.io/discord/1020742926856372224"/>
</a>

## Thank you

A big thank you ❤️ to these amazing people for contributing to this project!

<a href="https://github.com/wizarrrr/wizarr/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=wizarrrr/wizarr" />
</a>
