# Lentii Yahenskii

<h2 align="center">About me</h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ā” Quick bio:":                    "A kind of metalHead-synthWave-cyberPunk-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado hybrid",
		"- š­ Iām currently working on":      "Sharpen my programming knowledge",
		"- š± Iām currently learning":        "Golang, MongoDB, RabbitMQ, K8s, GCP",
		"- šÆ Iām looking to collaborate on": "Python, Golang and Docker related projects",
		"- š¤ Iām looking for help with":     "Anything related to what I am currently learning š",
		"- š¬ Ask me about":                  "Python, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev and SEO",
		"- š« How to reach me:":              "morrowcooper50@gmail.com",
	}
}
```
