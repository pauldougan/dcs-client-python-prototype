# dcs-client-python-prototype

A client for the Document Checking Service implemented in python for the Verify Q3 2019 🔥firebreak

- Trello: [Build a DCS client from scratch](https://trello.com/c/wAMBwrWI)
- Use the [public documentation for the DCS Pilot](https://dcs-pilot-docs.cloudapps.digital/) 

# Install prerequisite tools

Install Homebrew package installer
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Clone this repo
```
https://github.com/pauldougan/dcs-client-python.git
```

Install the tools
```
brew bundle
```

Install python dependencies
```
pip3 install -r requirements.txt
```

# Start prototyping

Get the code
```
git clone https://github.com/pauldougan/dcs-client-python-prototype.git
cd dcs-client-python-prototype
```

Start prototyping in Jupyter
```
jupyter notebook notebook/prototyping.ipynb
```

http://localhost:8888/tree

# Running the prototype

# Support

If something does not make sense [raise an issue](https://github.com/alphagov/dcs-pilot-docs/issues/new)

# References

| standard                                  | uri                                                               |
|: ----------------------------------------- | :----------------------------------------------------------------- |
|  A128CBC-HS256                            | https://www.rfc-editor.org/rfc/rfc7518.html#section-5.2.3         |
|  HTTP-Status-Code                         | https://www.rfc-editor.org/rfc/rfc2616.html#section-10            |
|  HTTP                                     | https://www.rfc-editor.org/info/rfc2616                           |
|  ISO 1601                                 | https://www.iso.org/iso-8601-date-and-time-format.html            |
|  JOSE                                     | https://jose.readthedocs.io/en/latest                             |
|  JSON Web Algorithms                      | https://www.rfc-editor.org/info/rfc7518                           |
|  JSON Web Encryption                      | https://www.rfc-editor.org/info/rfc7516                           |
|  JSON Web Key                             | https://www.rfc-editor.org/info/rfc7517                           |
|  JSON Web Signature                       | https://www.rfc-editor.org/info/rfc7515                           |
|  JSON                                     | https://www.rfc-editor.org/info/rfc8259                           |
|  JWA                                      | https://www.rfc-editor.org/info/rfc7518                           |
|  JWE                                      | https://www.rfc-editor.org/info/rfc7516                           |
|  JWK                                      | https://www.rfc-editor.org/info/rfc7517                           |
|  JWS                                      | https://www.rfc-editor.org/info/rfc7515                           |
|  JavaScript Object Notation               | https://www.rfc-editor.org/info/rfc8259                           |
|  JavaScript Object Signing and Encryption | https://jose.readthedocs.io/en/latest                             |
|  PKCS1                                    | https://www.rfc-editor.org/info/rfc2437                           |
|  REST                                     | https://restfulapi.net/                                           |
|  RFC 2437                                 | https://www.rfc-editor.org/info/rfc2437                           |
|  RFC 2616                                 | https://www.rfc-editor.org/info/rfc2616                           |
|  RFC 3447                                 | https://www.rfc-editor.org/info/rfc3447                           |
|  RFC 4122                                 | https://www.rfc-editor.org/info/rfc4122                           |
|  RFC 6712                                 | https://www.rfc-editor.org/info/rfc6712                           |
|  RFC 7515                                 | https://www.rfc-editor.org/info/rfc7515                           |
|  RFC 7516                                 | https://www.rfc-editor.org/info/rfc7516                           |
|  RFC 7517                                 | https://www.rfc-editor.org/info/rfc7517                           |
|  RFC 7518                                 | https://www.rfc-editor.org/info/rfc7518                           |
|  RFC 8017                                 | https://www.rfc-editor.org/info/rfc8017                           |
|  RFC 8259                                 | https://www.rfc-editor.org/info/rfc8259                           |
|  RSAES-OAEP                               | https://tools.ietf.org/html/rfc8017#section-7.1                   |
|  RSASSA-PKCS1-V1_5                        | https://www.rfc-editor.org/rfc/rfc8017.html#section-8.2           |
|  TLS                                      | https://www.rfc-editor.org/info/rfc5246                           |
|  UUID                                     | https://www.rfc-editor.org/info/rfc4122                           |
|  date time format                         | https://www.iso.org/iso-8601-date-and-time-format.html            |
|  github-issue                             | https://github.com/alphagov/dcs-pilot-docs/issues/new?labels=bug  |
|  jwe-alg-header                           | https://www.rfc-editor.org/rfc/rfc7516.html#section-4.1.1         |
|  jwe-enc-header                           | https://www.rfc-editor.org/rfc/rfc7516.html#section-4.1.2         |
|  jws-alg-header                           | https://www.rfc-editor.org/rfc/rfc7515.html#section-4.1.1         |

