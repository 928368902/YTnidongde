# YTnidongde (Y-Tian Branch Project) 🌥️

A Python SDK for Simplified Video API Integration

---

## Features ✨
- Search videos with flexible queries
- Retrieve detailed video metadata
- Easy to use
- Pagination support for bulk operations

---

## Installation ⚙️

```shell
pip install YTnidongde
```

---

## Quick Start 🚀

### Import Modules
```python
import search_api.client
import view_api.client
```

### Initialize Clients
```python
search_client = search_api.client.SearchClient()
view_client = view_api.client.ViewClient()
```

---

## Usage Examples 🎯

### 1. Video Search
```python
# Search for videos with pagination
result = search_client.search_videos(
    query="student",
    max_pages=2
)
```

### 2. Video Detail Retrieval
```python
# Get detailed metadata for a video
video_detail = view_client.get_video_detail("48777")  # Example video ID
```

---

## Client Methods Documentation 📖

### SearchClient Methods
| Method          | Parameters         | Description                     |
|------------------|--------------------|---------------------------------|
| `search_videos`  | query, max_pages   | Search videos with pagination   |

### ViewClient Methods
| Method               | Parameters | Description                      |
|----------------------|------------|----------------------------------|
| `get_video_detail`   | video_id   | Retrieve full video metadata     |

---


> **Note:** This is an unofficial SDK. Use according to platform API guidelines.
