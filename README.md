## Hi there, I'm Arki 👋

<a target="_blank" href="https://dev.to/@arki"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white"></img></a>
<a target="_blank" href="https://twitter.com/arkeazs"><img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=Twitter&logoColor=white"></img></a>
<a target="_blank" href="https://www.linkedin.com/in/antonio-arias-b4639b335/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></img></a>
<a target="_blank" href="https://gitlab.com/arkeaz"><img src="https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white"></img></a>
<a target="_blank" href="https://leetcode.com/u/arkeaz/"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black"></img></a>
<a target="_blank" href="https://www.hackerrank.com/profile/arkeaz"><img src="https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white"></img></a>
<a target="_blank" href="https://www.codewars.com/users/arkeasz"><img src="https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=Codewars&logoColor=white"></img></a>
<a target="_blank" href="https://codepen.io/arkeaz"><img src="https://img.shields.io/badge/Codepen-000000?style=for-the-badge&logo=codepen&logoColor=white"></img></a>
<a target="_blank" href="https://codeforces.com/profile/arkeaz"><img src="https://img.shields.io/badge/Codeforces-445f9d?style=for-the-badge&logo=Codeforces&logoColor=white"></img></a>
<a target="_blank" href="https://www.codechef.com/users/arkeaz"><img src="https://img.shields.io/badge/Codechef-%23B92B27.svg?&style=for-the-badge&logo=Codechef&logoColor=white"></img></a>
<a target="_blank" href="https://bio.link/arki"><img src="https://img.shields.io/badge/bio.link-000000%7D?style=for-the-badge&logo=biolink&logoColor=white"></img></a>


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
        backend: ["Ruby", "Node.js", "Go", "Rust"],
        frontend: ["HTML", "JavaScript", "Vue", "CSS"],
        database: ["PostgreSQL", "MySQL", "Redis"],
        cloud: ["AWS", "GCP", "DigitalOcean", "Heroku"],
        architecture: ["Microservices", "Event-driven", "Design Systems"],
    }
};

fn main() {
    println!("Meet {}: {:?}", ARKI.name, ARKI.skills);
}

```
