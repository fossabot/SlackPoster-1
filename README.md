# SlackPoster

[![SlackPoster](https://img.shields.io/nuget/v/SlackPoster)](https://www.nuget.org/packages/SlackPoster/)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyinyangtm%2FSlackPoster.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyinyangtm%2FSlackPoster?ref=badge_shield)


Post a message to Slack easily.

Slackへメッセージを投稿します。

---

## Getting started

Install SlackPoster nuget package.

NuGet パッケージ マネージャーからインストールしてください。

- [SlackPoster](https://www.nuget.org/packages/SlackPoster/)

> ```powershell
> Install-Package SlackPoster
> ```

---

## Basic Usage

```c#
// Init
var sp = new SlackPost("WEB HOOK URL");

// Post Message
sp.PostMessage("hello world.")

```




## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyinyangtm%2FSlackPoster.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyinyangtm%2FSlackPoster?ref=badge_large)