# GitFisher
## Python
A small application to clone public repos of specified accounts. 

### Setup 
----
#### *Dependencies:* 
`pip install requirments.txt`

#### *Config:*

```Json
{
  "users": [
    {
      "username": "Github Username"
    }
  ]
}
```
#### *.env:*

``` Text
MAILGUN_API_KEY= MailGun API Key
MY_EMAIL= Email to send
MY_NAME=  Name

```

### *Run*
`python GitFisher.py `

`python GitFisher.py -s` - Silent mode: no output

*#### MailGun:* 
This application intergrates [MailGun](https://www.mailgun.com/) to send updates via email.
