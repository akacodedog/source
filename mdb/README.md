### 關鍵修改
- 修改mdb.js的10342行

### 關鍵代碼
- !$(e.target).closest("#select-options-".concat(this.uuid)).length && !$(e.target).hasClass('mdb-select') && $("#select-options-".concat(this.uuid)).hasClass('active') && this.$materialSelect.trigger("close");