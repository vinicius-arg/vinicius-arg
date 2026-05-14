```c
#include <stdio.h>
#include "person.h"

void person_init(Person* me)
{
  me->name = "Vinicius";
  me->education = "Computer Engineering at UFS";
  me->os = "Linux Mint 22.1 x86_64";

  me->main_interests = (char*[]){
      "Computer Architecture",
      "Low-level Programming",
      "Embedded Systems"
  };

  me->additional_exp = (char*[]){ "Web Development" };
  me->hobbies = (char*[]){ "Guitar", "Cooking", "Everson Zoio" };
  me->assistant = "Sarah 🐈"; // Debugging partner;
}

int main()
{
  Person me;
  person_init(&me);

  printf("Welcome to my profile!\n");

  return 0;
}
```

### Brief Description

I enjoy low-level programming and most of my projects are focused on it. They're available in the pinned repos below, feel free to explore them.

### Contacts

Want to get in touch? Send me an e-mail by clicking [here](mailto:vinicius.argolo@dcomp.ufs.br).

(There's also [my Linkedin](https://www.linkedin.com/in/vinicius-arg), but it's still a little empty for now.)
