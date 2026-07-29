```mermaid
---
config:
  theme: base
  themeVariables:
    background: "#ffffff"
    primaryColor: "#080808"
    primaryTextColor: "#f5f5f5"
    primaryBorderColor: "#080808"
    lineColor: "#080808"
    fontFamily: "MaruBuri, serif"
  themeCSS: |
    .cardImage div {
      box-sizing: border-box;
      width: 1800px !important;
      height: 1000px !important;
      display: block !important;
      position: relative !important;
      background-image: url("https://raw.githubusercontent.com/OU9999/OU9999/main/assets/ou9999-card-bg.jpg") !important;
      background-size: cover !important;
      background-position: center !important;
    }
    .cardImage .nodeLabel {
      display: block !important;
      position: relative !important;
      width: 100% !important;
      height: 100% !important;
    }
    .cardImage .nodeLabel span {
      position: absolute !important;
      display: block !important;
      height: 51px !important;
      overflow: visible !important;
      white-space: nowrap !important;
      color: transparent !important;
      font-family: "MaruBuri", serif !important;
      font-size: 42px !important;
      font-style: normal !important;
      font-weight: 400 !important;
      line-height: 1 !important;
      background-repeat: no-repeat !important;
      background-position: left top !important;
      background-size: contain !important;
      user-select: text !important;
    }
    .cardImage .nodeLabel span:nth-child(1) {
      left: 69px;
      top: 55px;
      width: 158px !important;
      background-image: url("https://raw.githubusercontent.com/OU9999/OU9999/main/assets/card-text/name.png") !important;
    }
    .cardImage .nodeLabel span:nth-child(2) {
      right: 260px;
      top: 55px;
      width: 292px !important;
      background-image: url("https://raw.githubusercontent.com/OU9999/OU9999/main/assets/card-text/phone.png") !important;
    }
    .cardImage .nodeLabel span:nth-child(3) {
      left: 69px;
      bottom: 65px;
      width: 216px !important;
      background-image: url("https://raw.githubusercontent.com/OU9999/OU9999/main/assets/card-text/site.png") !important;
    }
    .cardImage .nodeLabel span:nth-child(4) {
      right: 260px;
      bottom: 60px;
      width: 469px !important;
      background-image: url("https://raw.githubusercontent.com/OU9999/OU9999/main/assets/card-text/email.png") !important;
    }
---
block
  visual["<span>OU9999</span><span>010-3625-0318</span><span>ou9999.me</span><span>omh232323@gmail.com</span>"]

  classDef cardImage fill:#080808,stroke:#080808,stroke-width:0px
  class visual cardImage
```
