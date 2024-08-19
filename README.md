```Golang
package main

import (
	"fmt"
	"os"
)

type User struct {
	Name                 string `json:"name"`
	Username             string `json:"username"`
	Bio                  string `json:"Bio"`
	Affiliation          string `json:"affiliation"`
	WorksAt              string `json:"works_at"`
	ProgrammingLanguages string `json:"programming_languages"`
	InterestedIn         string `json:"interested_in"`
}

func NewBIO() *User {
	return &User{
		Name:                 "Artyem",
		Username:             "wlcmtunknwndth",
		Bio:                  "Currently learning rust for highload purposes",
		Affiliation:          "People's Friendship University of Russia, Computer Science, bachelor",
		WorksAt:              "VK AI",
		ProgrammingLanguages: "go, rust, python",
		InterestedIn:         "backend, ml, ds",
	}
}

func main() {
	_, err := fmt.Fprintf(os.Stdout, "%+v", NewBIO())
	if err != nil {
		return
	}
	return
}
```

![GitHub Stats](https://github-readme-streak-stats.herokuapp.com/?user=wlcmtunknwndth&theme=default&hide_border=true) ![GitHub Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=wlcmtunknwndth&theme=default&show_icons=true&hide_border=true&layout=compact)

![LeetCode Stats](https://leetcard.jacoblin.cool/wlcmtunknwndth?theme=light&font=Asul&ext=activity)
