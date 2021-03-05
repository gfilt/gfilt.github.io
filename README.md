<h1 align="center">GFilt</h1>

<p align="center">
  <a href="https://gmail.com" target="_blank" rel="noreferrer">
    <img src="https://static.prasadt.com/logos/google/svg/gmail.svg" height="64" align="center" alt="gmail">
  </a>
</p>

<h4 align="center">A CLI app to manage GMail filters.</h4>

## About

Currently this app is private.

## Notes & Limitations

1. Please download your existing filters from the Web-UI, BEFORE using this tool.
1. GMail limits number of filters with forwarding action to 20.
1. This app will **NOT** take any actions on existing E-Mails.
1. Converting existing filters is experimental.

## Privacy & Security

1. This app is **NOT** yet verified.
1. This app communicates directly with GMail API and all tokens and credentials are **ONLY** stored **LOCALLY**.
1. You are welcome to set your own OAUTH app credentials, should you choose to.
4. This app has NO access to contents or metadata
   of your E-Mails.

## Permissions

| Reason             | Permission
|--------------------|---
| Manage labels      | `gmail.labels`
| Manage filters     | `gmail.settings.basic`
| Audit settings     | `gmail.settings.basic`
| Know your GMail ID | `userinfo.email`
