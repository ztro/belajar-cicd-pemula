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

