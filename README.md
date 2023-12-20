<!--
**Lancern/Lancern** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Hi there 👋

```rust
impl Lancern {
    pub fn about() -> Self {
        Self {
            name: "Sirui Mu",
            location: "Shanghai, China",
            email: "msrlancern@gmail.com",
        }
    }
}

impl Programmer for Lancern {
    fn topics(&self) -> Vec<&'static str> {
        vec!["Compilers & Toolchains", "Storage", "Backend", "Frontend"]
    }

    fn major_languages(&self) -> Vec<&'static str> {
        vec!["C/C++", "Rust", "C#", "TypeScript"]
    }
}

impl Educated for Lancern {
    fn bachelor() -> Degree {
        Degree("Beijing Institute of Technology", "Software Engineering", 2016..=2020)
    }

    fn master() -> Degree {
        Degree("Tsinghua University", "Cybersecurity", 2020..=2023)
    }
}

impl FormerACMer for Lancern { }
impl FormerCTFer for Lancern { }
```

[![Sirui's github stats](https://github-readme-stats.vercel.app/api?username=Lancern)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Lancern&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
