# Definitely «-apple-system»

This repository contains the awesome [Inter](https://rsms.me/inter/)
font renamed to *-apple-system*.

### Why?

Because so many websites have weird custom
font stacks instead of relying on [`system-ui`](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family#system-ui).

Some of them even have Roboto \*shudders\* before
a proper UI font like Helvetica or Arial (looking at you Azure DevOps).

The solution is simple: Most of them include `-apple-ui`,
so let's give the websites what they want :D

<details>
    <summary>Some examples</summary>

* Azure DevOps
  ```css
  font-family: "Segoe UI","-apple-system",BlinkMacSystemFont,Roboto,"Helvetica Neue",Helvetica,Ubuntu,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol"
  ```
* GitHub
  ```css
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji"
  ```
* Jira
  ```css
  font-family: -apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen,Ubuntu,Fira Sans,Droid Sans,Helvetica Neue,sans-serif
  ```

</details>
