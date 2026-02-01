# HEARTBEAT.md

## Tasks

### 1. Git Sync (Always)
워크스페이스 변경사항 확인 후 커밋 & 푸시:
```bash
cd /root/clawd && git status --porcelain
```
- 변경사항 있으면: `git add -A && git commit -m "Auto-sync: [brief description]" && git push`
- 변경사항 없으면: skip

### 2. Memory Cleanup (Weekly)
오래된 memory 파일 정리 - 7일 이상 지난 daily notes는 MEMORY.md로 요약 후 정리 고려.
