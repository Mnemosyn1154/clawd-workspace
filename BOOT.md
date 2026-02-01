# BOOT.md - Startup Tasks

Gateway 시작 시 자동 실행됨.

## Tasks

1. **Git Pull** - 원격 저장소에서 최신 변경사항 가져오기:
```bash
cd /root/clawd && git pull --ff-only 2>&1 || echo "Git pull skipped or failed"
```

2. **Create memory folder** (if needed):
```bash
mkdir -p /root/clawd/memory
```

완료 후 조용히 종료 (메시지 보내지 않기).
