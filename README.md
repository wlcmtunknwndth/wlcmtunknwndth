```Rust
use std::fmt;

#[derive(Debug)]
struct User {
    name: String,
    username: String,
    bio: String,
    works_at: String,
    programming_languages: String,
    interested_in: String,
}

impl User {
    fn new() -> Self {
        User {
            name: "Artyem".to_string(),
            username: "wlcmtunknwndth".to_string(),
            bio: "Currently learning rust for highload purposes".to_string(),
            works_at: "VK AI".to_string(),
            programming_languages: "go, rust, python".to_string(),
            interested_in: "backend, ml, ds".to_string(),
        }
    }
}

impl fmt::Display for User {
    fn fmt(&self, f: &mut fmt::Formatter) -> fmt::Result {
        write!(f, "User {{ name: {}, username: {}, bio: {}, works_at: {}, programming_languages: {}, interested_in: {} }}",
            self.name, self.username, self.bio, self.works_at, self.programming_languages, self.interested_in)
    }
}

fn main() {
    let user = User::new();
    println!("{}", user);
}
```

![GitHub Stats](https://github-readme-streak-stats.herokuapp.com/?user=wlcmtunknwndth&theme=default&hide_border=true) ![GitHub Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=wlcmtunknwndth&theme=default&show_icons=true&hide_border=true&layout=compact)

![LeetCode Stats](https://leetcard.jacoblin.cool/wlcmtunknwndth?theme=light&font=Asul&ext=activity)
