# gopagewok
to demostrate the golang workspace workflow

`gsoup` is a go html parser like inspired by jsoup
`goblog-ez` has the main module to parser [goblog](https://go.dev/blog/all) to json which use `gsoup` lib

this project pull both repos into workspace any updates in local `gsoup` will be see in `goblog-ez`

run `go run github.com/goxlarge/goblog-ez` to see the changes
