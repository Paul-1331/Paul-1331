```cpp
#include <life.h>
#include <wikipedia.h>  // dangerous import — use with caution

struct Paul {

    // identity
    const std::string  name           = "Paul Biju";
    const std::string  location       = "NIT Calicut, Kerala";
    const int          height         = 173;          // cm
    const std::string  display        = "boy";
    const std::string  spirit_animal  = "Garfield 🐱";

    // academics
    std::string        degree         = "B.Tech, Computer Science";
    std::string        institute      = "NIT Calicut";

    // interests
    std::vector<std::string> into = {
        "competitive programming",
        "theoretical CS",       // automata, complexity, the void
        "web development",
        "AI / ML",
        "quantitative finance"
    };

    // cp
    std::string  fav_problem_type  = "greedy";   // local optimum, trust
    std::string  grinding_on       = "Codeforces + Leetcode";

    // traits
    bool         night_owl         = true;
    bool         reads_papers      = true;
    bool         borderline_lazy   = true;   // yet somehow still here
    std::string  monday_opinion    = "strongly opposed";

    // WARNING: the following field has caused significant productivity loss.
    // do not enable unless you have 4+ hours to spare.
    WikipediaClient wiki;   // opens one tab. then another. then seventeen more.

    void say_hi() {
        // greedily takes the path of most interesting topic
        std::cout << "hey — glad you stopped by.\n";
        std::cout << "i'm probably awake right now. it's late.\n";
    }
};
```

---

### what I'm building

| project | stack | what |
|---|---|---|
| [GreedyArena](https://github.com/paulbiju) | React · TypeScript · Supabase | competitive quiz platform with real-time multiplayer + Glicko-2 ratings |

---

### find me

[![Codeforces](https://img.shields.io/badge/Codeforces-paulbiju-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/paulbiju)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-paulbiju-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/paulbiju)

---

<sub>NIT Calicut · Kerala, India · probably tabs, not spaces · hates Mondays</sub>
