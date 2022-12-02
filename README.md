# GraduationThesis-SarcasticData
졸업 논문: 뉴스 댓글에 나타난 비아냥 화행 데이터 분석

## 프로젝트 소개
22.06.01 치러진 전국동시지방선거 기간동안 작성된 정치면 뉴스 200개에 달린 댓글을 수집한 뒤, 댓글에서 나타나는 비꼬는 말하기의 양상을 분석하는 프로젝트입니다.

## 프로젝트 기간
- 22.03.02 ~ 22.12.28

### 개발 환경
- 'python'(주피터 노트북)

## 주요 과제
#### 수집할 뉴스 선정
- 뉴스 수집 사이트: 이용자가 많은 네이버와 다음의 정치면 뉴스
- 수집 기간: 05.30 ~ 06.03
- 선정 기준: 오전 10시와 오후 10시를 기준으로 댓글이 가장 많이 달린 뉴스 10개

#### 댓글 수집
- 원데이터 추출을 위해 클린봇, 세이프봇 적용 해제
- 고유 id, 댓글 내용, 뉴스 제목을 인덱스로 하는 데이터 프레임으로 정리

#### 댓글 분석
- 단순 비난
- 데이터 전처리를 통해 단순 비난 화행 삭제
- 데이터 토큰화 이후 비아냥 말하기 가설과 실제 비교
