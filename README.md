<h2>Description</h2>

Decrypts teamviewer passwords stored in windows registry

<h2>Finding Keys</h2>

`reg query HKLM\SOFTWARE\WOW6432Node\TeamViewer\Version<#>`

`reg query HKLM\SOFTWARE\WOW6432Node\TeamViewer\Version7 /v <key>`

<h4>Example Keys</h4>

SecurityPasswordExported

SecurityPasswordAES

ServerPasswordAES

ProxyPasswordAES

LicenseKeyAES

OptionsPasswordAES

OptionsPassword

PermanentPassword

<h2>Usage</h2>

`tvdecrypt <teamviewer key>`
