```c
#include <stdio.h>
#include "person.h"

void person_init(Person* me)
{
  // Basics
  me->name = "Vinicius";
  me->birthday = "22-08-2004";
  me->education = "Computer Engineering at UFS";
  me->os = "Linux Mint 22.1 x86_64"

  me->programming_languages = (char*[]){ "C/Cpp", "Java", "Python", "Verilog" };
  me->web_stack = (char*[]){ "HTML/CSS", "JavaScript", "React", "Node", "Express", "Mongo", "Postgre" };
  me->speaking_languages = (char*[]){ "Portuguese", "English" };

  me->hobbies = (char*[]){ "Guitar", "Cooking", "Everson Zoio" };

  // Contact
  me->academic_email = "vinicius.argolo@dcomp.ufs.br";
  me->work_email = "j.vinicius.arg@gmail.com";  
  me->linkedin = "linkedin.com/in/vinicius-arg";

  // Other
  me->current_focus = "Embedded Systems and IoT";
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
