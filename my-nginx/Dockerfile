# 1. 기존 베이스 이미지 선택 (공식 NGINX, alpine은 가벼운 버전)
FROM nginx:alpine

# 2. 기본 설정 파일을 내 설정으로 교체
COPY default.conf /etc/nginx/conf.d/default.conf

# 3. 기본 HTML을 내 정적 콘텐츠로 교체
COPY index.html /usr/share/nginx/html/index.html

# 4. 80번 포트를 사용함을 명시 (문서화 목적)
EXPOSE 80
