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
		"- ā” Quick bio:":                    "A kind of metalHead-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado hybrid",
		"- š­ Iām currently working on":      "Tredicom as a Senior Software Developer --- UAdeC as a Part Time Teacher",
		"- š± Iām currently learning":        "Golang, MongoDB, RabbitMQ, K8s, GCP (Tech stack from my company) --- Sharpening my Front End Skills for the MERN stack (Personal goal)",
		"- šÆ Iām looking to collaborate on": "Python, Golang and Docker related projects",
		"- š¤ Iām looking for help with":     "Anything related to what I am currently learning š",
		"- š¬ Ask me about":                  "Python, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev and SEO",
		"- š« How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}
