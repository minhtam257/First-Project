<div class="grid-layout">
  <div class="header">
    Thông tin
    <br>
    Họ tên: Nguyễn Ngọc Bảo Nghi
    <br>
    Ngày tháng năm sinh: 25/02/2010
    <br>
    Nơi ở: Việt Nam
    <br>
    Địa chỉ: Khu phố Phước Sơn - Thị trấn Đất Đỏ - Huyện Đất Đỏ - Tỉnh BRVT
  
  </div>
  <div class="sidebar">
    Giới thiệu bản thân
  <br>
    <img src="https://scontent.fsgn5-5.fna.fbcdn.net/v/t1.0-9/109553416_669636856921810_2953574435321858618_o.jpg?_nc_cat=100&_nc_sid=8bfeb9&_nc_ohc=KTWb1PGvw44AX-eY2cM&_nc_ht=scontent.fsgn5-5.fna&oh=2640642491e803fb7281db21e8a41c10&oe=5F469863">
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
