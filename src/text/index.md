---
layout: home
---

## 기초탄탄 Git
많은 개발자들이 `깃`의 사용법을 학습하여 사용을 하기를 바랍니다. 이를 위해서 `길벗`과 `저자`는 책의 내용를 학습사이트와 함께 같이 배포 합니다.

### 3장 깃 개념 잡기 65
* 3.1 깃 저장소 생성 68
    - 3.1.1 폴더와 깃 저장소 68
    - 3.1.2 초기화 68
    - 3.1.3 숨겨진 폴더 = .git 폴더 71
    - 3.1.4 소스트리와 연결 72
* 3.2 워킹 디렉터리 77
    - 3.2.1 워킹 디렉터리란? 78
    - 3.2.2 파일의 untracked 상태와 tracked 상태 78
* 3.3 스테이지 79
    - 3.3.1 스테이지 = 임시 영역 80
    - 3.3.2 파일의 stage 상태와 unstage 상태 80
    - 3.3.3 파일의 modified 상태와 unmodified 상태 81
* 3.4 파일의 상태 확인 83
    - 3.4.1 status 명령어로 깃 상태 확인 83
    - 3.4.2 소스트리에서 깃 상태 확인 83
* 3.5 파일 관리 목록에서 제외: .gitignore 84
    - 3.5.1 .gitignore 파일 85
    - 3.5.2 .gitignore 파일 표기법 85
* 3.6 깃 저장소 복제 86
    - 3.6.1 공개 저장소 87
    - 3.6.2 다운로드 vs 복제 87
    - 3.6.3 복제 명령어 88
* 3.7 정리 89

### 4장 커밋 91
4.1 코드의 변화 94
4.1.1 파일 관리 방법 95
4.2 새 파일 생성 및 감지 96
4.2.1 새 파일 생성 96
4.2.2 깃에서 새 파일 생성 확인 97
4.2.3 소스트리에서 새 파일 감지 98
4.3 깃에 새 파일 등록 99
4.3.1 스테이지에 등록 99
4.3.2 파일의 추적 상태 확인 102
4.3.3 파일 등록 취소 103
4.3.4 등록된 파일 이름이 변경되었을 때 105
4.4 첫 번째 커밋 106
4.4.1 HEAD 106
4.4.2 스냅샷 107
4.4.3 파일 상태와 커밋 108
4.5 커밋 확인 112
4.5.1 스테이지 초기화 112
4.5.2 로그 기록 확인 113
4.5.3 소스트리에서 로그 기록 확인 114
4.6 두 번째 커밋 115
4.6.1 파일 수정 115
4.6.2 파일 변경 사항 확인 116
4.6.3 수정된 파일 되돌리기 117
4.6.4 스테이지에 등록 117
4.6.5 두 번째 커밋 118
4.6.6 두 번째 커밋 확인 119
4.6.7 깃허브에서 확인 121
4.7 메시지가 없는 빈 커밋 122
4.7.1 세 번째 커밋 122
4.7.2 소스트리에서 빈 커밋 123
4.7.3 빈 커밋 확인 123
4.8 커밋 아이디 125
4.8.1 SHA1 125
4.8.2 단축키 126
4.9 커밋 로그 126
4.9.1 간략 로그 126
4.9.2 특정 파일의 로그 127
4.10 diff 명령어 128
4.10.1 파일 간 차이 128
4.10.2 워킹 디렉터리 vs 스테이지 영역 128
4.10.3 커밋 간 차이 130
4.10.4 소스트리에서 간단하게 변경 이력 확인 130
4.10.5 diff 내용을 추가하여 커밋 131
4.11 정리 132

### 5장 서버 133
5.1 서버 저장소 137
5.1.1 협업 저장소 137
5.1.2 연속된 작업 137
5.1.3 새 멤버 138
5.2 깃허브 서버 준비 138
5.2.1 깃허브 138
5.2.2 저장소 생성 139
5.3 깃허브 연동 및 원격 등록 141
5.3.1 로컬 저장소 141
5.3.2 프로토콜 142
5.3.3 원격 저장소의 리모트 목록 관리 144
5.3.4 주소와 별칭 144
5.3.5 원격 저장소에 연결 145
5.3.6 소스트리에서 원격 브랜치 145
5.3.7 별칭 이름 변경과 정보 146
5.3.8 원격 서버 삭제 147
5.4 서버 전송 148
5.4.1 push: 서버에 전송 148
5.5 자동으로 내려받기 150
5.5.1 clone: 복제 150
5.5.2 pull: 서버에서 내려받기 151
5.6 수동으로 내려받기 154
5.6.1 자동 병합 154
5.6.2 fetch: 가져오기 154
5.6.3 merge 명령어로 수동 병합 157
5.7 순서 158
5.7.1 최신 상태 158
5.7.2 충돌 방지 159
5.8 정리 160

### 6장 브랜치 161
6.1 새로운 작업 163
6.1.1 브랜치 작업 163
6.1.2 깃 브랜치 특징 164
6.2 실습 준비 165
6.2.1 저장소 생성 및 초기화 165
6.2.2 기본 브랜치 166
6.3 브랜치 생성 166
6.3.1 브랜치 생성 167
6.3.2 브랜치 이름 169
6.3.3 소스트리 브랜치 170
6.4 브랜치 확인 172
6.4.1 간단 브랜치 목록 172
6.4.2 브랜치 해시 173
6.4.3 브랜치 세부 사항 확인 173
6.5 브랜치 이동 174
6.5.1 체크아웃 174
6.5.2 브랜치 동작 원리 176
6.5.3 소스트리 176
6.5.4 이전 브랜치 177
6.5.5 워킹 디렉터리 정리 177
6.6 브랜치 공간 179
6.6.1 브랜치 로그 179
6.6.2 브랜치 소스 확인 180
6.7 HEAD 포인터 181
6.7.1 마지막 커밋 181
6.7.2 브랜치 HEAD 182
6.7.3 소스트리 HEAD 183
6.7.4 상대적 위치 183
6.7.5 AHEAD, BHEAD 184
6.8 생성과 이동 185
6.8.1 자동 이동 옵션 185
6.8.2 커밋 이동 186
6.8.3 HEAD를 활용한 이동 188
6.8.4 돌아오기 188
6.9 원격 브랜치 189
6.9.1 리모트 브랜치 189
6.9.2 실습 준비 190
6.9.3 브랜치 추적 191
6.9.4 브랜치 업로드 191
6.9.5 이름이 다른 브랜치 194
6.9.6 업스트림 트래킹 195
6.9.7 원격 브랜치 복사 200
6.9.8 업스트림 연결 203
6.10 브랜치 전송 205
6.10.1 브랜치 푸시 205
6.10.2 브랜치 페치 207
6.11 브랜치 삭제 208
6.11.1 일반적인 삭제 방법 208
6.11.2 강제로 삭제하는 방법 209
6.11.3 소스트리에서 삭제하는 방법 210
6.11.4 리모트 브랜치를 삭제하는 방법 211
6.12 정리 212

### 7장 임시 처리 213
7.1 스태시 217
7.1.1 기존 작업 도중에 새로운 변경 요청 218
7.1.2 새 코드 작성 중 기존 코드를 수정 220
7.1.3 스태시의 임시 스택 영역에 작업 중인 코드 저장 221
7.1.4 임시 저장 영역의 스택 목록 223
7.1.5 임시 저장한 스태시 불러오기 224
7.1.6 스태시 복원으로 충돌 226
7.1.7 스태시 복사 228
7.1.8 스태시 삭제 230
7.1.9 소스트리에서 스태시 사용 231
7.2 워킹 디렉터리 청소 232
7.3 정리 234

### 8장 병합과 충돌 235
8.1 병합 238
8.1.1 하나씩 직접 비교하는 수동 병합 238
8.1.2 깃으로 자동 병합 239
8.1.3 병합 방식 240
8.2 Fast-Forward 병합 241
8.2.1 브랜치 생성과 수정 작업 242
8.2.2 병합 위치 246
8.2.3 Fast-Forward 병합 적용 248
8.3 3-way 병합 250
8.3.1 브랜치 생성과 수정 작업 250
8.3.2 마스터 변경 253
8.3.3 공통 조상 256
8.3.4 병합 커밋 257
8.3.5 병합 메시지 258
8.4 브랜치 삭제 260
8.4.1 병합 후 삭제 260
8.5 충돌 261
8.5.1 충돌이 생기는 상황 261
8.5.2 실습을 위한 충돌 만들기 261
8.5.3 수동으로 충돌 해결 266
8.5.4 소스트리에서 충돌 해결 268
8.6 브랜치 병합 여부 확인 270
8.7 리베이스 271
8.7.1 베이스 271
8.7.2 베이스 변경 271
8.7.3 리베이스 vs 병합 272
8.7.4 리베이스 명령어 273
8.7.5 리베이스 병합 277
8.7.6 리베이스되었는지 확인 278
8.7.7 리베이스 후 브랜치 279
8.7.8 리베이스 충돌과 해결 281
8.7.9 rebase 명령어로 커밋 수정 286
8.7.10 리베이스할 때 주의할 점 288
8.8 정리 288

### 9장 복귀 289
9.1 되돌리기 292
9.1.1 다시 시작 292
9.2 리셋 296
9.2.1 복귀 시점 296
9.2.2 reset 명령어 297
9.2.3 soft 옵션 298
9.2.4 mixed 옵션 301
9.2.5 hard 옵션 304
9.2.6 소스트리 306
9.2.7 커밋 합치기 307
9.2.8 스테이지 리셋 310
9.2.9 작업 취소 310
9.2.10 병합 취소 311
9.2.11 주의할 점 313
9.3 리버트 314
9.3.1 취소 커밋 314
9.3.2 리버트 지정 318
9.3.3 소스트리에서 리버트 318
9.3.4 병합 취소 319
9.3.5 리버트 히스토리 322
9.4 정리 322

### 10장 배포 관리와 태그 325
10.1 배포 327
10.2 버전 327
10.3 태그 329
10.4 태그 목록 329
10.5 Annotated 태그 331
10.5.1 태그 생성 331
10.5.2 간단한 메시지 333
10.5.3 소스트리에서 태그 생성 334
10.5.4 태그는 중복해서 생성할 수 없다 336
10.5.5 태그 삭제 338
10.5.6 태그의 상세 정보 확인: show 명령어 339
10.6 Lightweight 태그 340
10.6.1 체크섬 340
10.6.2 태그의 상세 정보 확인 341
10.7 특정 커밋 태그 342
10.7.1 소스트리에서 특정 커밋 지정 343
10.8 태그를 사용한 체크아웃 344
10.8.1 태그 브랜치 345
10.9 태그 공유 346
10.9.1 원격 저장소 생성 346
10.9.2 태그 동기화 348
10.9.3 전체 태그 동기화 350
10.9.4 원격 저장소의 태그 수정과 삭제 352
10.9.5 원격 저장소에 로컬과 다른 이름으로 태그 전송 354
10.10 정리 357

### 11장 서브모듈 359
11.1 대형 프로젝트 361
11.1.1 저장 용량 361
11.1.2 저장소 분리 361
11.1.3 상하 관계 362
11.2 실습을 위한 저장소 준비 362
11.2.1 메인 저장소 생성 363
11.2.2 자식 저장소 생성 365
11.3 서브모듈 추가 367
11.3.1 저장소 연결 368
11.3.2 설정 파일 369
11.3.3 모듈 커밋 370
11.4 서브모듈 작업 371
11.4.1 모듈 저장소 371
11.4.2 모듈 상태 372
11.4.3 모듈 커밋 374
11.4.4 부모 커밋 375
11.5 자식 저장소 갱신 377
11.5.1 자식 저장소 378
11.5.2 자식 저장소 갱신 378
11.5.3 자식 저장소 작업 379
11.5.4 부모 저장소 적용 380
11.5.5 부모 저장소 갱신 382
11.6 부모 저장소 복제 383
11.6.1 부모 저장소 복제 383
11.6.2 모듈 업데이트 384
11.7 부모 저장소 업데이트 385
11.7.1 부모 업데이트 386
11.7.2 부모 저장소로 풀 386
11.8 정리 386

### 12장 고급 기능 387
12.1 refs 388
12.1.1 실습 환경 준비 388
12.1.2 해시 389
12.1.3 역조회 390
12.1.4 참조 목록 390
12.2 reflog 391
12.2.1 참조 기록 391
12.2.2 기록 확인 392
12.2.3 기간 확인 393
12.2.4 기록 유지 393
12.3 파일 애너테이션 393
12.3.1 blame 394
12.3.2 실습 환경 준비 394
12.3.3 blame 명령어 395
12.3.4 옵션 활용 395
12.4 replace 396
12.4.1 실습 환경 준비 397
12.4.2 저장소 분리 399
12.4.3 저장소 분리 402
12.4.4 저장소 연결 405
12.5 가비지 콜렉트 407
12.5.1 가비지 407
12.5.2 압축 관리 408
12.5.3 실행 408
12.5.4 refs 압축 408
12.5.5 환경 설정 409
12.6 prune 409
12.6.1 고립된 객체 409
12.6.2 실습 환경 준비 410
12.6.3 객체 삭제 411
12.6.4 객체 정리 413
12.6.5 원격 작업 415
12.7 rerere 416
12.7.1 동일한 충돌 416
12.7.2 활성화 416
12.7.3 실습 준비 417
12.7.4 충돌 및 기록 419
12.7.5 자동 해결 422
12.8 정리 424