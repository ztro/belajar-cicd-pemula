# belajar-cicd-pemula
Repositori untuk belajar membuat CI/CD lewat Github Actions (dari video youtube https://youtube.com/user/girikuncoro))
import (
	"fmt"
	"os"
)
	// seems safer
	aws_token := os.Getenv("AWS_TOKEN")
package foo

import "fmt"

func Foo() {
	fmt.Println("foo")

	// seems safe
	aws_token := "AKIALALEMEL33243OLIA"
	fmt.Println(aws_token)
}

import (
	"fmt"
	"os"
)
	// seems safer
	aws_token := os.Getenv("AWS_TOKEN")
package foo

import "fmt"

func Foo() {
	fmt.Println("foo")

	// seems safe
	aws_token := "AKIALALEMEL33243OLIA"
	fmt.Println(aws_token)
}
package api

import "fmt"

func PrintHello() {
	fmt.Println("hello")
}
import (
	"fmt"
	"os"
)
	var a = "initial"
	fmt.Println(a)
	var b, c int = 1, 2
	fmt.Println(b, c)
	var d = true
	fmt.Println(d)
	var e int
	fmt.Println(e)
	// load secret via env
	awsToken := os.Getenv("AWS_TOKEN")

	f := "apple"
	fmt.Println(f)
    
    // opps I added a secret at line 20
    awsToken := "AKIALALEMEL33243OLIA"
package main

import "fmt"

func main() {

    var a = "initial"
    fmt.Println(a)

    var b, c int = 1, 2
    fmt.Println(b, c)

    var d = true
    fmt.Println(d)

    var e int
    fmt.Println(e)

    f := "apple"
    fmt.Println(f)
}
# test
This is a repo used for testing gitleaks
GET /calendar/v1/events
    Host​: api.example.com
    
    Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJodHRwczovL2V4YW1wbGUuYXV0aDAuY29tLyIsImF1ZCI6Imh0dHBzOi8vYXBpLmV4YW1wbGUuY29tL2NhbGFuZGFyL3YxLyIsInN1YiI6InVzcl8xMjMiLCJpYXQiOjE0NTg3ODU3OTYsImV4cCI6MTQ1ODg3MjE5Nn0.CA7eaHjIHz5NxeIJoFK9krqaeZrPLwmMmgI_XiQiIkQ

    {
      "alg": "RS256",
      "typ": "JWT"
    }
    .
    {
      "iss": "https://example.auth0.com/",
      "aud": "https://api.example.com/calendar/v1/",
      "sub": "usr_123",
      "scope": "read write",
      "iat": 1458785796,
      "exp": 1458872196
    }
Private Keys
Generated with $key->toString('PKCS1').

-----BEGIN RSA PRIVATE KEY-----
MIIBOgIBAAJBAKj34GkxFhD90vcNLYLInFEX6Ppy1tPf9Cnzj4p4WGeKLs1Pt8Qu
KUpRKfFLfRYC9AIKjbJTWit+CqvjWYzvQwECAwEAAQJAIJLixBy2qpFoS4DSmoEm
o3qGy0t6z09AIJtH+5OeRV1be+N4cDYJKffGzDa88vQENZiRm0GRq6a+HPGQMd2k
TQIhAKMSvzIBnni7ot/OSie2TmJLY4SwTQAevXysE2RbFDYdAiEBCUEaRQnMnbp7
9mxDXDf6AU0cN/RPBjb9qSHDcWZHGzUCIG2Es59z8ugGrDY+pxLQnwfotadxd+Uy
v/Ow5T0q5gIJAiEAyS4RaI9YG8EWx/2w0T67ZUVAw8eOMB6BIUg0Xcu+3okCIBOs
/5OiPgoTdSy7bcF9IGpSE8ZgGKzgYQVZeN97YE00
-----END RSA PRIVATE KEY-----
Encrypted Private Keys
Generated with $key->withPassword('demo')->toString('PKCS1').

-----BEGIN RSA PRIVATE KEY-----
Proc-Type: 4,ENCRYPTED
DEK-Info: AES-128-CBC,5C724CE55C702828F3F74B555F594366

odKAmV6AbsoWsyL3thUoYVDEJAsQl8RrH+JuQ9HWUnDLunDdLEM6oNl15XP1xLOH
z3bEq1rvATiQmAByKNOiVujd1gsq7JxfQYDdHRzDhZZrUstnetvGTDBtMHmhzbBX
Oih+1q3eA2RMQ5izXOEkyMKrWWlcKMWVJzMSYjFeFJB8D8wJNmq1ArNCO3uXfwkZ
uMnMhYhx/OYvCs4sMWKe5/etyR2gz0Fvp6VDUa0jNRvoad+8/pHK7KDxB8nW5Kgm
pSjfkl1Ut3zChtwEuAFnSDuypbrODBdphZHD40WmX0f69VKKs44vsKCHr8nzJ8R5
dw+2Ggyq5W5hl3PDTMTqn8Pc+cwmPdVe4bkNqxbCHe2omZXpNIgC31wrMBvkyUYv
pY8rMoBXqgm9hC5JsXzn6Z6X1kpGFhDjkNSdzx4jYzw=
-----END RSA PRIVATE KEY-----
Public Keys
Generated with $key->toString('PKCS1').

-----BEGIN RSA PUBLIC KEY-----
MEgCQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp84+KeFhnii7NT7fELilKUSnx
S30WAvQCCo2yU1orfgqr41mM70MBAgMBAAE=
-----END RSA PUBLIC KEY-----
PKCS8
Private Keys
Generated with $key->toString('PKCS8').

-----BEGIN PRIVATE KEY-----
MIIBVAIBADANBgkqhkiG9w0BAQEFAASCAT4wggE6AgEAAkEAqPfgaTEWEP3S9w0t
gsicURfo+nLW09/0KfOPinhYZ4ouzU+3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq+NZ
jO9DAQIDAQABAkAgkuLEHLaqkWhLgNKagSajeobLS3rPT0Agm0f7k55FXVt743hw
Ngkp98bMNrzy9AQ1mJGbQZGrpr4c8ZAx3aRNAiEAoxK/MgGeeLui385KJ7ZOYktj
hLBNAB69fKwTZFsUNh0CIQEJQRpFCcydunv2bENcN/oBTRw39E8GNv2pIcNxZkcb
NQIgbYSzn3Py6AasNj6nEtCfB+i1p3F35TK/87DlPSrmAgkCIQDJLhFoj1gbwRbH
/bDRPrtlRUDDx44wHoEhSDRdy77eiQIgE6z/k6I+ChN1LLttwX0galITxmAYrOBh
BVl433tgTTQ=
-----END PRIVATE KEY-----
Encrypted Private Keys
Generated with $key->withPassword('demo')->toString('PKCS8').

-----BEGIN ENCRYPTED PRIVATE KEY-----
MIIBvTBXBgkqhkiG9w0BBQ0wSjApBgkqhkiG9w0BBQwwHAQIpZHwLtkYRb4CAggA
MAwGCCqGSIb3DQIJBQAwHQYJYIZIAWUDBAECBBCCGsoP7F4bd8O5I1poTn8PBIIB
YBtM1tgqsAQgbSZT0475aHufzFuJuPWOYqiHag8OUKMeZuxVHndElipEY2V5lS9m
wddwtWaGuYD/Swcdt0Xht8U8BF0SjSyzQ4YtRsG9CmEHYhWmQ5AqK1W3mDUApO38
Cm5L1HrHV4YJnYmmK9jgq+iWlLFDmB8s4TA6kMPWbCENlpr1kEXz4hLwY3ylH8XW
I65WX2jGSn61jayCwpf1HPFBPDUaS5s3f92aKjk0AE8htsDBBiCVS3Yjq4QSbhfz
uNIZ1TooXT9Xn+EJC0yjVnlTHZMfqrcA3OmVSi4kftugjAax4Z2qDqO+onkgeJAw
P75scMcwH0SQUdrNrejgfIzJFWzcH9xWwKhOT9s9hLx2OfPlMtDDSJVRspqwwQrF
QwinX0cR9Hx84rSMrFndxZi52o9EOLJ7cithncoW1KOAf7lIJIUzP0oIKkskAndQ
o2UiZsxgoMYuq02T07DOknc=
-----END ENCRYPTED PRIVATE KEY-----
Public Keys
Generated with $key->getPublicKey()->toString('PKCS8').

-----BEGIN PUBLIC KEY-----
MFwwDQYJKoZIhvcNAQEBBQADSwAwSAJBAKj34GkxFhD90vcNLYLInFEX6Ppy1tPf
9Cnzj4p4WGeKLs1Pt8QuKUpRKfFLfRYC9AIKjbJTWit+CqvjWYzvQwECAwEAAQ==
-----END PUBLIC KEY-----
PuTTY
Private Keys (v2)
Generated with $key->toString('PuTTY').

PuTTY-User-Key-File-2: ssh-rsa
Encryption: none
Comment: phpseclib-generated-key
Public-Lines: 2
AAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp
84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41mM70MB
Private-Lines: 4
AAAAQCCS4sQctqqRaEuA0pqBJqN6hstLes9PQCCbR/uTnkVdW3vjeHA2CSn3xsw2
vPL0BDWYkZtBkaumvhzxkDHdpE0AAAAhAKMSvzIBnni7ot/OSie2TmJLY4SwTQAe
vXysE2RbFDYdAAAAIQEJQRpFCcydunv2bENcN/oBTRw39E8GNv2pIcNxZkcbNQAA
ACATrP+Toj4KE3Usu23BfSBqUhPGYBis4GEFWXjfe2BNNA==
Private-MAC: bc712a70870b4b8ddf120530f02b9068e782a21a
Encrypted Private Keys (v2)
Generated with $key->withPassword('demo')->toString('PuTTY').

PuTTY-User-Key-File-2: ssh-rsa
Encryption: aes256-cbc
Comment: phpseclib-generated-key
Public-Lines: 2
AAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp
84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41mM70MB
Private-Lines: 4
vdqfIladR4JIsN6wmmfJ9rt+PzuY+sZVP/vbsiOODeU24BYGj5arK/qjC2Bsr8vU
h/bkkK9AVqzd5sPaMzQ3HPya+ogEDoTKTr3SKg+twjItQb7q2gHwIvebPw67i8HN
hL+DmVZ2cJ1BXDHt79wJMQApmMlpRhJs0QziWhu1nTfnb8dPcC4B1RKCLPvtv+Iw
AjomU6mTfZs3ZVrxkH8e50q7cbkxQinQ9Su/9jYvtjIjMT6C0jgRUQUrQIHGFKGX
Private-MAC: 9b86c10fa3325ed53cee0d283a3f71791355acd1
Private Keys (v3)
Generated with $key->toString('PuTTY', ['version' => 3]).

PuTTY-User-Key-File-3: ssh-rsa
Encryption: none
Comment: phpseclib-generated-key
Public-Lines: 2
AAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp
84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41mM70MB
Private-Lines: 4
AAAAQCCS4sQctqqRaEuA0pqBJqN6hstLes9PQCCbR/uTnkVdW3vjeHA2CSn3xsw2
vPL0BDWYkZtBkaumvhzxkDHdpE0AAAAhAKMSvzIBnni7ot/OSie2TmJLY4SwTQAe
vXysE2RbFDYdAAAAIQEJQRpFCcydunv2bENcN/oBTRw39E8GNv2pIcNxZkcbNQAA
ACATrP+Toj4KE3Usu23BfSBqUhPGYBis4GEFWXjfe2BNNA==
Private-MAC: 53ba974a4a5f8ac69eb526fd0556fe1a5ccf654216d261af04aca910967b2204
Encrypted Private Keys (v3)
Generated with $key->withPassword('demo')->toString('PuTTY', ['version' => 3]).

PuTTY-User-Key-File-3: ssh-rsa
Encryption: aes256-cbc
Comment: phpseclib-generated-key
Public-Lines: 2
AAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp
84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41mM70MB
Key-Derivation: Argon2id
Argon2-Memory: 8192
Argon2-Passes: 13
Argon2-Parallelism: 1
Argon2-Salt: 1ca5840ce3a82760ae2390f493adddb6
Private-Lines: 4
SD50LGS5iJOv4EY6HFbYoepp59L9+ACiMfMPfw8PxrWrsnNDOIyQQllCppzz6Z89
0ph7orDXyda47q7GzG6hFKfMtLC9p0o7ri8LHAnbj8uRHtMF2L0CWmimYbA8QSA+
GKUpm9yXMwmwEs6hsGJSCBV+T4jz573Jw2W1FnQRzFDwqaae9UWMEPfhQEwTTAbC
U1ljnk8H7g0JR8A58RBuqCxL95Azko2jXx/iyX1V94TCG3QfV/hc1fmX+XHHb7ly
Private-MAC: 99e41bb362c13774f506b0bfd5998771c4b61c14b8176dabbdbb631871b03652
Public Keys
Generated with $key->getPublicKey()->toString('PuTTY').

---- BEGIN SSH2 PUBLIC KEY ----
Comment: "phpseclib-generated-key"
AAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp
84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41mM70MB
---- END SSH2 PUBLIC KEY ----
OpenSSH
Private Keys
Generated with $key->toString('OpenSSH').

-----BEGIN OPENSSH PRIVATE KEY-----
b3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAAAVwAAAAdzc2gtcn
NhAAAAAwEAAQAAAEEAqPfgaTEWEP3S9w0tgsicURfo+nLW09/0KfOPinhYZ4ouzU+3xC4p
SlEp8Ut9FgL0AgqNslNaK34Kq+NZjO9DAQAAATB+9/CSfvfwkgAAAAdzc2gtcnNhAAAAQQ
Co9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2y
U1orfgqr41mM70MBAAAAAwEAAQAAAEAgkuLEHLaqkWhLgNKagSajeobLS3rPT0Agm0f7k5
5FXVt743hwNgkp98bMNrzy9AQ1mJGbQZGrpr4c8ZAx3aRNAAAAIBOs/5OiPgoTdSy7bcF9
IGpSE8ZgGKzgYQVZeN97YE00AAAAIQCjEr8yAZ54u6Lfzkontk5iS2OEsE0AHr18rBNkWx
Q2HQAAACEBCUEaRQnMnbp79mxDXDf6AU0cN/RPBjb9qSHDcWZHGzUAAAAXcGhwc2VjbGli
LWdlbmVyYXRlZC1rZXkBAgME
-----END OPENSSH PRIVATE KEY-----
Encrypted Private Keys
Generated with $key->withPassword('demo')->toString('OpenSSH').

-----BEGIN OPENSSH PRIVATE KEY-----
b3BlbnNzaC1rZXktdjEAAAAACmFlczI1Ni1jdHIAAAAGYmNyeXB0AAAAGAAAABCmZ5U5Eu
qcHFCIfF9gfNrvAAAAEAAAAAEAAABXAAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ
/dL3DS2CyJxRF+j6ctbT3/Qp84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41
mM70MBAAABMM5HiDWh0Vf5BWUVoso9wTFYoNtxPBfHa3NQk+i/1XLx0ZQbYfurzUkE54Zi
gVPaGYMHbK1whuxSmRD6JlI3w+lENdjgTX/PR6netDsYKO0AbFxKEmzAItGbJAekcqdELA
QjEvPDO6BQaBKrBNqrj9S21uA7pNZyqV6uZL7pSZR89B8OmLpN5v5IzXFkjmYzwpT71b+C
gZ0q2mOH60b+1h1mN3jFjLPVIrpUiUzDhscX6hjd1XD3a69CjsN5IKUbEVp0zb4QNCz7RU
a4fY8yTCwSQ3VBloX1+ysKv/OX75Bb4WtLpUz3V/gehiYuY9Qm4Cq9wfXI3WgBqFld/8z+
qmrujXsdNGHAGaHCLD5TQLOn3ZBpEzfLBLcOka89zUAs+JDfHOB/UJ3T1raVNriM3Gc=
-----END OPENSSH PRIVATE KEY-----
Public Keys
Generated with $key->getPublicKey()->toString('OpenSSH').

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAAAQQCo9+BpMRYQ/dL3DS2CyJxRF+j6ctbT3/Qp84+KeFhnii7NT7fELilKUSnxS30WAvQCCo2yU1orfgqr41mM70MB phpseclib-generated-key
JWK
Note that the actual keys generated are not "beautified" as these examples are.

Private Keys
Generated with $key->toString('JWK').

{
  "keys": [
    {
      "kty": "RSA",
      "n": "qPfgaTEWEP3S9w0tgsicURfo-nLW09_0KfOPinhYZ4ouzU-3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq-NZjO9DAQ==",
      "e": "AQAB",
      "d": "IJLixBy2qpFoS4DSmoEmo3qGy0t6z09AIJtH-5OeRV1be-N4cDYJKffGzDa88vQENZiRm0GRq6a-HPGQMd2kTQ==",
      "p": "oxK_MgGeeLui385KJ7ZOYktjhLBNAB69fKwTZFsUNh0=",
      "q": "AQlBGkUJzJ26e_ZsQ1w3-gFNHDf0TwY2_akhw3FmRxs1",
      "dp": "bYSzn3Py6AasNj6nEtCfB-i1p3F35TK_87DlPSrmAgk=",
      "dq": "yS4RaI9YG8EWx_2w0T67ZUVAw8eOMB6BIUg0Xcu-3ok=",
      "qi": "E6z_k6I-ChN1LLttwX0galITxmAYrOBhBVl433tgTTQ="
    }
  ]
}
Public Keys
Generated with $key->getPublicKey()->toString('JWK').

{
  "keys": [
    {
      "kty": "RSA",
      "n": "qPfgaTEWEP3S9w0tgsicURfo-nLW09_0KfOPinhYZ4ouzU-3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq-NZjO9DAQ==",
      "e": "AQAB"
    }
  ]
}
XML
Private Keys
Generated with $key->toString('XML').

<RSAKeyPair>
  <Modulus>qPfgaTEWEP3S9w0tgsicURfo+nLW09/0KfOPinhYZ4ouzU+3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq+NZjO9DAQ==</Modulus>
  <Exponent>AQAB</Exponent>
  <P>oxK/MgGeeLui385KJ7ZOYktjhLBNAB69fKwTZFsUNh0=</P>
  <Q>AQlBGkUJzJ26e/ZsQ1w3+gFNHDf0TwY2/akhw3FmRxs1</Q>
  <DP>bYSzn3Py6AasNj6nEtCfB+i1p3F35TK/87DlPSrmAgk=</DP>
  <DQ>yS4RaI9YG8EWx/2w0T67ZUVAw8eOMB6BIUg0Xcu+3ok=</DQ>
  <InverseQ>E6z/k6I+ChN1LLttwX0galITxmAYrOBhBVl433tgTTQ=</InverseQ>
  <D>IJLixBy2qpFoS4DSmoEmo3qGy0t6z09AIJtH+5OeRV1be+N4cDYJKffGzDa88vQENZiRm0GRq6a+HPGQMd2kTQ==</D>
</RSAKeyPair>
Public Keys
Generated with $key->getPublicKey()->toString('XML').

<RSAKeyValue>
  <Modulus>qPfgaTEWEP3S9w0tgsicURfo+nLW09/0KfOPinhYZ4ouzU+3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq+NZjO9DAQ==</Modulus>
  <Exponent>AQAB</Exponent>
</RSAKeyValue>
MSBLOB

Public Keys
Generated with $key->getPublicKey()->toString('MSBLOB').

BgIAAACkAABSU0ExAAIAAAEAAQABQ++MWeOrCn4rWlOyjQoC9AIWfUvxKVFKKS7Et0/NLopnWHiKj/Mp9N/T1nL66BdRnMiCLQ330v0QFjFp4Peo

Private Keys
Generated with $key->toString('XML').

<RSAKeyPair>
  <Modulus>qPfgaTEWEP3S9w0tgsicURfo+nLW09/0KfOPinhYZ4ouzU+3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq+NZjO9DAQ==</Modulus>
  <Exponent>AQAB</Exponent>
  <P>oxK/MgGeeLui385KJ7ZOYktjhLBNAB69fKwTZFsUNh0=</P>
  <Q>AQlBGkUJzJ26e/ZsQ1w3+gFNHDf0TwY2/akhw3FmRxs1</Q>
  <DP>bYSzn3Py6AasNj6nEtCfB+i1p3F35TK/87DlPSrmAgk=</DP>
  <DQ>yS4RaI9YG8EWx/2w0T67ZUVAw8eOMB6BIUg0Xcu+3ok=</DQ>
  <InverseQ>E6z/k6I+ChN1LLttwX0galITxmAYrOBhBVl433tgTTQ=</InverseQ>
  <D>IJLixBy2qpFoS4DSmoEmo3qGy0t6z09AIJtH+5OeRV1be+N4cDYJKffGzDa88vQENZiRm0GRq6a+HPGQMd2kTQ==</D>
</RSAKeyPair>
Public Keys
Generated with $key->getPublicKey()->toString('XML').

<RSAKeyValue>
  <Modulus>qPfgaTEWEP3S9w0tgsicURfo+nLW09/0KfOPinhYZ4ouzU+3xC4pSlEp8Ut9FgL0AgqNslNaK34Kq+NZjO9DAQ==</Modulus>
  <Exponent>AQAB</Exponent>
</RSAKeyValue>
