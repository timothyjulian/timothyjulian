# Hi 👋
```rust
// src/main.rs

fn main() {
    let timothy = SoftwareEngineer::new("Timothy Julian", "Software Development Engineer", vec!["id_ID", "en_US"]);

    timothy.say_hi();
}

struct SoftwareEngineer {
    name: &'static str,
    role: &'static str,
    languages: Vec<&'static str>,
}

impl SoftwareEngineer {
    fn new(name: &'static str, role: &'static str, languages: Vec<&'static str>) -> Self {
        SoftwareEngineer { name, role, languages }
    }

    fn say_hi(&self) {
        println!(
            "👋 Hi, I'm {} — a passionate {}.\nI speak: {}",
            self.name,
            self.role,
            self.languages.join(", ")
        );
    }
}
```

## 📝 Blogs
- Personal blog & portfolio: [https://timothyjulian.github.io](https://timothyjulian.github.io/)

## 📊 My Most Used Languages

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs?username=timothyjulian&theme=dark&layout=compact"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs?username=timothyjulian&layout=compact"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=timothyjulian&layout=compact" />
</picture>
