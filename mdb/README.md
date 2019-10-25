# 關鍵修改

mdb.js的10342行需修改為!$(e.target).closest("#select-options-".concat(this.uuid)).length && !$(e.target).hasClass('mdb-select') && $("#select-options-".concat(this.uuid)).hasClass('active');