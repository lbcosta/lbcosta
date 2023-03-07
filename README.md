<h2>
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2ZlYWU2NzI2NWE4NGZiZWJmNzVkZTJkYTZhMTg0NTE5MzllYTRhYSZjdD1z/m7GCmngo33rsmjxoPM/giphy.gif" width="50">
   Ahoy, fellow coder! I'm Leo!
</h2>

- 🌱 I’m currently learning `Observability, Domain Driven Design and Production-Ready Microservices`
- 🤔 I’m looking for help with `Finding a new day job!`
- 👨‍💻 A little _bit_ about me:

```go
package main

import "fmt"

type BackendEngineer struct {
	Name         string
	Code         []string
	AskMeAbout   []string
	Technologies map[string][]string
	CurrentFocus string
	FunFact      string
}

func (BackendEngineer) Greetings() {
	fmt.Println("Hello! Thanks for reading my profile. If you wanna know more about me, my contacts are listed below 😁")
}

func main() {
	Leo := BackendEngineer{}

	Leo.Name = "Leonardo Costa"
	Leo.Code = []string{"Go", "NodeJS", "ReactJS", "Typescript"}
	Leo.AskMeAbout = []string{"music", "boardgames", "movies", "tech"}
	Leo.Technologies = map[string][]string{
		"DevOps":   {"AWS", "Docker", "GCP"},
		"Database": {"Postgres", "MySQL", "Redis", "MongoDB"},
		"Misc":     {"Web sockets", "Python", "Flask", "Pandas"},
	}
	Leo.CurrentFocus = "Building Production Ready Microservices (following Susan J. Fowler checklist)"
	Leo.FunFact = "I was a drummer in an Arctic Monkeys cover band"

	Leo.Greetings()
}

```

<h2> 📫 How to reach me </h2>

- LinkedIn: https://www.linkedin.com/in/lbcosta/
- Telegram: https://t.me/lbcosta
- Email: lbcosta.dev@gmail.com
