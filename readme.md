{% comment %}

# This team hasn't started yet...

Check back later!

**Please read `tasks.md` to start your work.**

{% endcomment %}

### **Introduction**
Our team will do
- Task 1) Staring issues
- Task 2) Project board
- Task 3) Set up readme.md
- Task 4) Write C code
- Task 5) Get a status badge
- Task 6) Showcase your team
- Task 7) Register your repo
 
### **Code**
```c
{% include_relative code.c %}
```
![badge](https://github.com/div1121/project-team-a-try/blob/master/image_for_c.JPG?raw=true)

![example workflow](https://github.com/csci3251-2022/project-team-a/actions/workflows/c-cpp.yml/badge.svg)

### **Contribution**
{% for staff_member in _stu %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
