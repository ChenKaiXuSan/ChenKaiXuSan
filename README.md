# About Me

```python
from typing import Tuple, List, Dict
import datetime

class ChenKaiXu:
    pass

class Attributes(ChenKaiXu):
    @property
    def contact(self) -> Tuple[str, str, str]:

        email    = "chenkaixusan@gmail.com"
        google_scholar = "https://scholar.google.com/citations?user=kpNboagAAAAJ"
        blog     = "https://chenkaixusan.github.io/blog/"
        linkedin = "https://www.linkedin.com/in/chenkaixusan/"

        return email, google_scholar, blog, linkedin

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Chinese', 'English', 'Japanese']
        age   = datatime.datetime.now().year - 1996

        return langs, age

    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['jave', 'c++'],
            'learning'    : ['c', 'c#', 'php']
        }
        specialities  = ['AI application engineering', 'web/app development']
        research topic = ['AI', 'health care', 'deep learning']
        ide           = ['vscode']
        pc            = {
            'MacOS': {
                'macmini m1': {
                    'processor': 'm1 | 8 cores',
                    'ram'      : '16gb',
                    'gpu'      : 'm1 | 8 cores'
                },
				'macbook pro': {
					'processor': 'm5 | 10 cores',
                    'ram'      : '24gb',
                    'gpu'      : 'm5 | 10 cores'
            },
            'Windows': {
                'custom': {
                    'OS'       : 'Windows 11',
                    'processor': 'AMD ryzen 7 5700X | 8 cores',
                    'ram'      : '64gb 2400',
                    'gpu'      : 'nvidia 3080'
                }
            }
        }

	return langs, specialities, research topic, ide, pc
```

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=chenkaixusan" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=chenkaixusan&layout=compact&langs_count=8&card_width=320" />
</a>

# Skills

[![My Skills](https://skillicons.dev/icons?i=js,aws,bash,cs,cpp,django,docker,flask,git,github,linux,md,php,py,pytorch,qt,raspberrypi,vim,vscode,vue,)](https://skillicons.dev)
