# Django Chat Application
간단한 채팅 애플리케이션입니다.


## 기술 스택
- Django: 웹 프레임워크
- JavaScript, HTML, CSS: 프론트엔드 구현

## 설치 및 실행 방법

1. **프로젝트 클론**

   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

3. **가상 환경 생성 및 활성화**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows의 경우: venv\Scripts\activate
   ```

4. **필요 패키지 설치**

   ```bash
   pip install -r requirements.txt
   ```

5. **마이그레이션 수행**

   ```bash
   python manage.py migrate
   ```

6. **서버 실행**

   ```bash
   python manage.py runserver
   ```

7. **서버 확인**

   브라우저 또는 API 클라이언트를 통해 [http://127.0.0.1:8000](http://127.0.0.1:8000)으로 접근하여 API를 테스트합니다.

## 사용법

1. 회원가입 후 로그인합니다.
2. 새로운 채팅방을 생성하거나, 기존 채팅방에 참가합니다.
3. 채팅창에서 실시간으로 메시지를 주고받을 수 있습니다.

# 기여

버그 제보, 개선 사항 제안 및 코드 기여를 환영합니다. 기여를 원하시면 새로운 브랜치를 생성하여 PR(Pull Request)을 생성해주세요.

---

이 문서가 프로젝트를 이해하고 사용하는 데 도움이 되길 바랍니다. 질문이 있는 경우 Issues 섹션에 남겨주세요.
