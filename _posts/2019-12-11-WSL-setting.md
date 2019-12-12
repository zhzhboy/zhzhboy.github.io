---
title: "WSL2 설정법"
date: 2019-12-11T23:08:00-05:00
categories:
  - 개발환경
tags:
  - WSL
  - OpenFOAM
---

## WSL 설정 
WSL2를 사용하기 위해 Windows 10 빌드 18917 이상인지 확인
```bash
#Windows 빌드 확인
ver
```

WSL 활성화
'''bash
#Windows 가상 머신 활성화
Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform
wsl --set-version Ubuntu 2
'''

You'll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
