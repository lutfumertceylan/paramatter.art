---
layout: default
---

<h1 align="center">
  <br>
  <a href=""><img src="https://raw.githubusercontent.com/lutfumertceylan/top25-parameter/master/top25.jpg" alt=""></a>
</h1>
<h4 align="center">For basic researches, top 25 vulnerability parameters that can be used in automation tools or manual recon</h4>
<p align="center">
  <a href=""><img src="https://img.shields.io/github/v/release/lutfumertceylan/top25-parameter?style=flat"></a>
  <a href=""><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat"></a>
  <a href="https://twitter.com/intent/follow?screen_name=lutfumertceylan"><img src="https://img.shields.io/twitter/follow/lutfumertceylan?style=flat&logo=twitter"></a>
  <a href="https://github.com/lutfumertceylan"><img src="https://img.shields.io/github/stars/lutfumertceylan?style=flat&logo=github"></a>
</p>

---

## What is top25-parameter?

For basic researches, top 25 vulnerable parameters based on frequency of use with reference to various articles. These parameters can be used for automation tools or manual recon. Although the prevalence percentages of these parameters cannot be proven precisely, they were prepared by the TR Bug Hunters Community, which I founded, and myself.

This repo contains common parameters of the following vulnerabilities:
  
```
- Cross-Site Scripting (XSS)
- Server-Side Request Forgery (SSRF)
- Local File Inclusion (LFI)
- SQL Injection (SQLi)
- Remote Code Execution (RCE) - [for GET and POST methods]
- Open Redirect
```



## ToC
- [Cross-Site Scripting](#top-25-cross-site-scripting-xss-parameters-for-trbughunters-openbugbounty)
- [Server-Side Request Forgery](#top-25-server-side-request-forgery-ssrf-parameters-for-trbughunters)
- [Local File Inclusion](#top-25-local-file-inclusion-lfi-parameters-for-trbughunters)
- [SQL Injection](#top-25-sql-injection-parameters-for-trbughunters)
- [Remote Code Execution](#top-25-remote-code-execution-rce-parameters-get-based-for-trbughunters)
- [Open Redirect](#top-25-open-redirect-parameters-for-lutfumertceylan)

---

### Top 25 **Cross-Site Scripting (XSS)** Parameters for @trbughunters @openbugbounty

```json
{
    "flags": "-iE",
     "patterns": [

        "q=",
        "s=",
        "search=",
        "id=",
        "lang=",
        "keyword=",
        "query=",
        "page=",
        "keywords=",
        "year=",
        "view=",
        "email=",
        "type=",
        "name=",
        "p=",
        "month=",
        "image=",
        "list_type=",
        "url=",
        "terms=",
        "categoryid=",
        "key=",
        "l=",
        "begindate=",
        "enddate="
]
}
```

### Top 25 **Server-Side Request Forgery (SSRF)** Parameters for @trbughunters

```json
{
    "flags": "-iE",
     "patterns": [

        "dest=",
        "redirect=",
        "uri=",
        "path=",
        "continue=",
        "url=",
        "window=",
        "next=",
        "data=",
        "reference=",
        "site=",
        "html=",
        "val=",
        "validate=",
        "domain=",
        "callback=",
        "return=",
        "page=",
        "feed=",
        "host=",
        "port=",
        "to=",
        "out=",
        "view=",
        "dir="
]
}
```

### Top 25 **Local File Inclusion (LFI)** Parameters for @trbughunters

```json
```

### Top 25 **SQL Injection** Parameters for @trbughunters

```json
{
    "flags": "-iE",
     "patterns": [

        "id=",
        "page=",
        "report=",
        "dir=",
        "search=",
        "category=",
        "file=",
        "class",
        "url=",
        "news=",
        "item=",
        "menu=",
        "lang=",
        "name=",
        "ref=",
        "title=",
        "view=",
        "topic=",
        "thread=",
        "type=",
        "date=",
        "form=",
        "main=",
        "nav=",
        "region="
]
}
```

### Top 25 **Remote Code Execution (RCE)** Parameters [GET based] for @trbughunters

```json
{
    "flags": "-iE",
     "patterns": [

        "cmd=",
        "exec=",
        "command=",
        "execute=",
        "ping=",
        "query=",
        "jump=",
        "code",
        "reg=",
        "do=",
        "func=",
        "arg=",
        "option=",
        "load=",
        "process=",
        "step=",
        "read=",
        "feature=",
        "exe=",
        "module=",
        "payload=",
        "run=",
        "print="
]
}
```

### Top 25 **Open Redirect** Parameters for @lutfumertceylan

```json
{
    "flags": "-iE",
     "patterns": [

        "next=",
        "url=",
        "target=",
        "rurl=",
        "dest=",
        "destination=",
        "redir=",
        "redirect_uri",
        "redirect_url=",
        "redirect=",
        "out=",
        "view=",
        "to=",
        "image_url=",
        "go=",
        "return=",
        "returnTo=",
        "return_to=",
        "checkout_url=",
        "continue=",
        "return_path="
]
}
```
