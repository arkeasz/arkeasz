## Hi there, I'm Arki 👋

<a target="_blank" href="https://dev.to/@arki"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white"></img></a>
<a target="_blank" href="https://twitter.com/arkeazs"><img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=Twitter&logoColor=white"></img></a>

```rs
struct Profile {
    name: &'static str,
    pronouns: [&'static str; 2],
    skills: Skills
}

struct Skills {
    backend: [&'static str; 3],
    frontend: [&'static str; 4],
    database: [&'static str; 3],
    cloud: [&'static str; 4],
    architecture: [&'static str; 3],
}

const ARKI: Profile = Profile {
    name: "Arki",
    pronouns: ["He", "Him"],
    skills: Skills {
        backend: ["Ruby", "Node.js", "Go"],
        frontend: ["HTML", "JavaScript", "React", "CSS"],
        database: ["PostgreSQL", "MySQL", "Redis"],
        cloud: ["AWS", "GCP", "DigitalOcean", "Heroku"],
        architecture: ["Microservices", "Event-driven", "Design Systems"],
    }
};

fn main() {
    println!("Meet {}: {:?}", ARKI.name, ARKI.skills);
}

```
