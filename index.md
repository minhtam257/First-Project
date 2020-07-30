<div class="grid-layout">
  <div class="header">
    Thông tin
    <br>
    Họ tên: Nguyễn Ngọc Bảo Nghi
    Ngày tháng năm sinh: 
  
  </div>
  <div class="sidebar">Giới thiệu bản thân
    <img src=https://www.facebook.com/photo?fbid=669636853588477&set=pob.100016265058027>
  </div>
  <div class="content">
    Sở thích
    <br>
    Nghịch điện thoại, còn lại thì hong biết
  </div>
  <div class="footer">Bài viết được thực hiện bởi Tâm</div>
</div>
<style>
.grid-layout {
  display: grid;
  grid-gap: 10px;
  grid-template-columns: repeat(3, 1fr);
  grid-template-areas:
    'sidebar header header'
    'sidebar content content'
    'sidebar footer  footer';
  color: white;
}
.grid-layout > div {
  background: #333;
  padding: 10px;
}
.sidebar {
  grid-area: sidebar;
  text-align: center;
}
.content {
  grid-area: content;
}
.header {
  grid-area: header;
}
.footer {
  grid-area: footer;
}
</style>
