# Introduction

- Task 1: Starting issues

- Task 2: Project board

- Task 3: Set up readme.md

- Task 4: Show your team to the Internet

- Task 5: Keep checking

- Task 6: Write C code

- Task 7: Get a status badge

- Task 8: Promote your repo

# Code

#include<stdio.h>

int main()

{

    printf("Hello World");
    
    return 0;
    
}

# Contributors
{% for member in site.stu %}
    <img src="{{member.image}}">
    <p>{{member.user}}({{member.name}})</p>
    <p>{{member.content | markdownify}}</p>
{% endfor %}

 
