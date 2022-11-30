# 깃허브 생성
깃허브 생성하고 index.html을 삽입하였다
잘 나오는 것을 확인했다.
![](/assets/indexhtml.png)
# 루비 설치 jekyll 설치 기본테마 설치
루비설치 후 gem 을 이용하여 jekyll을 설치하고 기본테마를 설치하였다.
![](/assets/gem.png)
![](/assets/origin.png)
# 테마적용
여러 테마를 확인하며 돌아다니다 이 테마를 찾게 되었다. 세번의 시도가 있었는데 처음은 bundle install을 해도 오류가 나서 gemfile을 구글링 한대로 고쳤는데도 에러가 발생했다 두번째는 gemfile을 수정해서 localhost에서는 정상적으로 동작하는데 github에서는 메인화면에서의 포스트 업데이트가 작동하지 않았다. 하여 이 태마로 정착하게 되었다.
# 댓글 삽입
Disqus에서 아이디를 만들어
_includes/disqus.html을 만들어 _layouts/post.html에서 불러와주었다.
![](/assets/dis.png)
![](/assets/com.png)
# Google Analytics 삽입
글을 포스트했으니 읽어보면 좋겠다.
[**Google Analytics**](/_posts/2022-11-29-google-analytics.markdown)