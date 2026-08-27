# BIKINI CITY WORLD ARCHIVE v2

「비키니 시티 1차(1).docx」를 Canon source로 삼아 구축한 데이터 기반 정적 프론트엔드입니다.

## 실행
```bash
python -m http.server 8080
```
그 다음 `http://localhost:8080` 접속.

## 데이터
`public/data/`에 다음 JSON이 연결되어 있습니다.
- characters.json
- abilities.json
- ability-classes.json
- ranks.json
- factions.json
- organizations.json
- locations.json
- eras.json
- events.json
- relationships.json
- terms.json
- artifacts.json

장문 원문은 각 레코드의 `source_text` 및 개별 서사 필드에 보존되어 있습니다.
