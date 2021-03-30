# Bootstrap Portfolio
This template uses [Bootstrap](https://getbootstrap.com/), a fast and responsive front-end toolkit for building websites.
![Bootstrap Logo](assets/bootstrap_logo.png)

## Design Goals
Our goal for this bootstrap portfolio template was to guide a user through their resume, showcasing their publications, work experience and their past projects in an easy, eye-pleasing way.

Our design had three main goals:
1. The design should be _structurally sound_.
1. The design should be _eye-catching_ to potential employers.
1. The design should guide employers through the user's resume.

In a field such as computer science, where employers must sift through thousands of resumes, it is especially important to stand out from the crowd. Any design for a personal website should stand out among the thousands of job entries on the employers' desks, and it should guide the employer through the information as naturally as possible.

### About
We decided to make this more of a standard monolithic page due to the simplicity of the information presented. This page should have a cover statement or introduction, educational history and skills. This is also a great place to share your hobbies.

### Publications
While not necessarily required for every computer scientist, many STEM workers like to show off any publication they have in peer reviewed journals s well as any blogs they write. This can be a great way to show potential employers your experience, and publications can be a good deciding factor for employment or research grants.

> If you don't have any blogs or publications, don't worry about it! It is incredibly easy to remove that page. Follow the instructions below to find out how.

1. Delete [src/publications.html](src/work.html)
1. Remove **Publications** from the nav-bar.
```html
<ul class="nav navbar-nav">
  <li><a href="../index.html">About</a></li>
  <li><a href="projects.html">Projects</a></li>
  <li><a href="publications.html">Publications</a></li>
  <li class="active"><a href="#">Work</a></li>
</ul>
```
```html
<ul class="nav navbar-nav">
  <li><a href="../index.html">About</a></li>
  <li><a href="projects.html">Projects</a></li>
  <li class="active"><a href="#">Work</a></li>
</ul>
```

### Work
Showing your work experience as a time line can be an incredibly effective way of organizing that information for your employers. First of all, they are going to  want to see your most recent employment first and your least recent employment last. By placing it as a timeline, not only is everything balanced out side to side, but employers can be naturally guided back through your work history seeing the most relevant work first.

### Projects
This is a good place to talk about specific work you've done, either while employed, or on your own. Share your open source projects, Hackathons and anything else you're proud of. By organizing information into flip cards, all of the necessary information is kept in one place for any given project while not feeling too cluttered at any given time. The user is never presented with the information that they are not actively reading at the time.


## Who Are We?
**Jacob McAfoos** is a second semester senior at the University of Pittsburgh. He is majoring in computer science, and is going to be working in software development at Cigna in 2021. He considers himself to be a huge nerd and enjoys playing board games and dungeons and dragons.

**Joel Julin** is a sophomore computer science student at the University of Pittsburgh. Following his undergraduate career, he plans on pursuing interests in AI and computer vision through a master's degree. In his free time, he enjoys playing video games and spending time with friends. 

**Andrew Smith** is a sophomore majoring in mechanical engineering at the University of Pittsburgh.  After graduating with a bachelor's degree, he hopes to immediately gain hands on experience in the field.  In his spare time, he plays more video games with his friends than he probably should.  