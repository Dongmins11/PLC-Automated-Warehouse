# 프로젝트 파일 안내

[README로 돌아가기](../README.md)

## 원본 구성

| 저장소 파일 | 제공 자료에서의 출처 |
|---|---|
| `plc/warehouse.gxw` | 미니프로젝트 폴더에 직접 포함된 `미니프로젝트 합본.gxw` (1,203,712 bytes) |
| `plc/alternate/warehouse-from-archive.gxw` | 내부 `미니프로젝트 합본.zip`에 포함된 별도 `.gxw` (1,196,544 bytes) |
| `hmi/project/` | `project` 폴더 전체 |
| `config/motor-settings.pcw` | `모터세팅.pcw` |
| `config/motor-settings.png` | `모터세팅.png` |
| `assets/videos/demo-01.mp4` | `시연영상.mp4` |
| `assets/videos/demo-02.mp4` | `시연 영상.mp4` |
| `docs/presentation.pptx` | 제공된 발표자료 원본 |
| `docs/presentation-script.txt` | 신동민 발표 대본 원문 |

두 GX Works2 파일은 서로 다릅니다. 폴더에 직접 포함된 파일을 대표 경로에 배치했으며, 최종본 여부나 변경 관계를 단정하지 않았습니다. 원본 파일의 내용은 수정하지 않았습니다. SHA-256과 파일 크기는 `source-manifest.json`에 기록했습니다.

## 확인 방법

1. 저장소를 다운로드하거나 clone합니다.
2. GX Works2에서 `plc/warehouse.gxw`를 열어 프로젝트 설정과 래더를 확인합니다. 별도 보관본과 비교할 때는 `plc/alternate/`의 파일을 사용합니다.
3. HMI는 `hmi/project/` 폴더 전체를 유지한 상태에서 GT Designer3로 확인합니다. 제공된 `Project.gt32`는 0바이트이고 `_hdb` 등 관련 파일이 함께 있어, 파일 하나만 옮기지 않습니다.
4. 모터 설정 화면은 `config/motor-settings.png`, 원본 설정은 `.pcw` 파일을 참고합니다.

문서 정리 시 GX Works2·GT Designer3에서 프로젝트 열기 및 실제 장비 동작 검증은 수행하지 않았습니다. 설치 버전과 HMI 프로젝트 정상 열기 여부는 별도 확인이 필요합니다.

## 설명의 근거

- 전체 시스템·HMI·비트 단위 위치 관리: 제공 발표자료 및 발표 대본.
- 신동민 담당 범위·배출 동작·인터락: 신동민 발표 대본의 배출 관련 설명.
- 발표자료는 적재 기능을 중심으로 설명하므로 전체 공정의 참고 자료로 사용했습니다.
- 트러블슈팅은 대본에 실제 발생 사례로 기록된 내용만 정리했습니다. 성능 수치나 확인되지 않은 테스트 결과는 추가하지 않았습니다.
- 디바이스 할당표 이미지는 발표자료에서 추출한 화면입니다. 편집 가능한 원본 스프레드시트는 이번 제공 폴더에서 확인되지 않았습니다.
- 기간·팀 인원은 자료에서 확정하지 않아 README에 기재하지 않았습니다.

## 미디어

장비와 HMI 이미지는 발표자료의 원본 이미지입니다. 시연 영상 두 개는 원본을 함께 보존했습니다. README에서 영상 링크를 열어 확인하거나 파일을 다운로드할 수 있습니다.
