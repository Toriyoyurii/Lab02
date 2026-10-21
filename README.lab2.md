# Lab02 - Linked List, Stack və Queue Verilənlər Strukturlarının Tətbiqi, Təhlili və Müqayisəsi

## Tələbə Məlumatları
- **Ad və Soyad:** Fatimə Quliyeva
- **Qrup:** KOM25
- **İxtisas:** Kompüter mühəndisliyi
- **Müəllim:** Şamil Hümbətov

---

## Layihə Haqqında
Bu laboratoriya işi çərçivəsində hazır STL konteynerlərindən istifadə edilmədən, sıfırdan pointer/reference əlaqələri vasitəsilə **Linked List**, **Stack** və **Queue** verilənlər strukturları implementasiya edilmişdir. Hər bir struktur üzrə real həyat ssenariləri modelləşdirilmiş və müxtəlif həcmlərdə (100, 1000, 10000 element) eksperimental performans testləri aparılmışdır.

---

## Repozitoriya Strukturu
- `src/` - Python mənbə kodları
- `screenshots/` - Proqramın işləmə və nəticə skrinşotları
- `report/report.pdf` - Laboratoriya hesabatının PDF versiyası
- `test_results/` - Aparılan eksperimentlərin nəticə faylları
---

## Yerinə Yetirilmiş Tapşırıqlar

### Tapşırıq 1: Smart Music Playlist (Linked List)
- **Implementasiya olunan siniflər:** `SongNode`, `Playlist`
- **Əsas əməliyyatlar:** `addSong()`, `deleteSong()`, `searchSong()`, `displayPlaylist()`, `countSongs()`, `playNextSong()`

### Tapşırıq 2: Browser Undo History (Stack)
- **Implementasiya olunan siniflər:** `ActionNode`, `UndoStack` (LIFO prinsipi)
- **Əsas əməliyyatlar:** `pushAction()`, `undoAction()`, `currentAction()`, `displayHistory()`, `countActions()`

### Tapşırıq 3: University Printing Service (Queue)
- **Implementasiya olunan siniflər:** `PrintJobNode`, `PrintQueue` (FIFO prinsipi)
- **Əsas əməliyyatlar:** `enqueue()`, `dequeue()`, `peek()`, `displayQueue()`, `countJobs()`

---

## İcra Təlimatı (How to Run)
Proqramı işə salmaq üçün terminalda müvafiq skript faylını icra edin:

```bash
python src/main.py