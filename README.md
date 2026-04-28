```cpp
#include <life.h>
#include <pain.h>       // was already included in life.h
#include <wikipedia.h>  // dangerous import — use with caution

struct Paul {

    // identity
    const std::string  name           = "Paul Biju";
    const std::string  location       = "NIT Calicut, Kerala";
    const int          height         = 173;          // cm
    const int          age            = 20;           // year
    const std::string  display        = "boy";
    const std::string  spirit_animal  = "Garfield 🐱";

    // academics
    std::string        degree         = "B.Tech, Computer Science and Engineering";
    std::string        institute      = "NIT Calicut";
    const int          sem            = 4;
    const float        cgpa           = 9.67;         // it's all downhill from here    

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
        std::cout << "hey — glad you stopped by.\n";
        std::cout << "i'm probably awake right now. it's late.\n";
    }
};
```

---

### Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paul-biju-cheeramvelil-047541332)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/StrangeSet)

---

<sub>NIT Calicut · Kerala, India · probably tabs, not spaces · hates Mondays</sub>
