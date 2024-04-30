<h2 align="left">Hi 👋! My name is Guillem Dolcet and I'm a Fullstack Developer</h2>

###

<div align="left">
  <a href="mailto:g.dolcet.jove@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  </a>
  <a href="https://linkedin.com/in/guillem-dolcet" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
  </a>
</div>

###

```
<?php

namespace GuillemDolcet;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'INSON S.A.',
                'position' => 'Fullstack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            Sql::class,
            Html::class,
            Css::class,
            Git::class,
            Docker::class
        ];
    }
}
```
