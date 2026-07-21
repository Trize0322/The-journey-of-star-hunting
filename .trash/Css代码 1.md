/* 信息卡片样式 */
.book-card {
  background: var(--background-secondary);
  border-left: 4px solid var(--interactive-accent);
  padding: 12px 16px;
  margin: 16px 0;
  border-radius: 6px;
}

/* 书名和标签的布局 */
.book-title {
  font-weight: bold;
  font-size: 1.1em;
  display: flex;
  align-items: center;
  gap: 8px;
  flex-wrap: wrap;
}

/* 标签样式 */
.tag {
  background: var(--background-modifier-hover);
  padding: 2px 10px;
  border-radius: 12px;
  font-size: 0.8em;
  font-weight: normal;
}

/* 彩色标签 */
.tag-pink { background: #f9a8d4; color: #4a044e; }
.tag-blue { background: #93c5fd; color: #1e3a8a; }
.tag-green { background: #86efac; color: #14532d; }