For committing changes: git commit - m "message" || git push

For publishing changes: 

hugo new  --kind project project/test-project

avishekanand$ academic import --bibtex /Users/avishekanand/web/anand-academic-kickstart/content/publication/refs.bib


CV is under -- public/files

Images for Posts are under -- public/project/
	- Also under resources


Most of the written sections -- content/home/


Tutorial: [1] https://youtu.be/BHpkLJieXPE

Bio: content/authors/admin/index/

Projects: content/project/...

Publications: at 45 mins in [1]


Where are menus ?

-- config/_default/menus.toml

How to publish ?

-- git config --global user.name "avishekanand"
>> git config --global user.email "avishekanand@gmail.com"
>> git config -l
>> git config --global credential.helper cache

The last command is to cache the credentials

Instead of password give the TOKEN