# gopagewok
This project demostrates the golang workspace workflow
see [gsoup](https://github.com/goxlarge/gsoup) and [goblog-ez](https://github.com/goxlarge/goblog-ez)  

`gsoup` is a go html parser like inspired by jsoup
`goblog-ez` has the main module to parser [goblog](https://go.dev/blog/all) to json which use `gsoup` lib

1. clone `gsoup`
2. clone `goblog-ez`
3. make update in `gsoup`
4. reference updated code in `goblog-ez`
5. Run command `go run github.com/goxlarge/goblog-ez` to see the changes

BG: This project pull both repos into workspace any updates in local `gsoup` will be see in `goblog-ez`
