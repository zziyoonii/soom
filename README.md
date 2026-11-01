# 숨 · 같이 쉬어가는 요가원

말없이 같이 머무는 온라인 요가원. 노을 지는 섬 위 샬라에서 다른 방문객들과 나마스테로 인사하고, 아사나를 하거나 같이 호흡해요.

## 할 수 있는 것

- **나마스테**: 근처 사람들에게 인사 (1 키)
- **아사나**: 나무 자세 · 아래를 보는 개 · 아이 자세 · 누워 쉬기 (2 키)
- **호흡**: Inhale 4초 · Exhale 6초 가이드 (3 키)
- **함께 수련**: 한국 시간 07:00 · 19:00 · 22:00 정각에 접속자 전원이 같은 시퀀스를 함께 해요
- **매트 이용료**: 자율 후원 (🧘 버튼)

이동은 바닥 클릭이나 WASD, 시점은 드래그, 확대/축소는 휠로 해요.

## 실시간 접속 켜기

`index.html` 맨 위쪽 두 줄에 Supabase 값을 넣으면 실제 방문객끼리 연결돼요. 비워두면 시뮬레이션 방문객이 돌아다니는 데모 모드로 열려요.

```js
const SUPABASE_URL = 'https://xxxx.supabase.co';
const SUPABASE_KEY = '...anon 또는 publishable 키...';
```

Supabase Realtime의 Broadcast와 Presence만 써서 테이블은 필요 없어요. `?room=이름`을 붙이면 방을 나눌 수 있어요.

## 배포

빌드 없는 정적 페이지예요. Vercel에서 이 저장소를 Import하면 바로 배포돼요.

---

만든 사람 · 김지윤 (Qoo) · [@qooqoo.haseyo](https://www.instagram.com/qooqoo.haseyo/)
