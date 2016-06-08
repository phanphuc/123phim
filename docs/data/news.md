# News

### Request
```
GET [API_PATH]/data/news?type=4

type_id:
    1=Tin điện ảnh
    4=Tin reviews
    8=Tin khuyến mãi
```

### Response
```json
{
    "status": 1,
    "result": [{
        "news_id": 4229,
        "news_title": "[Lotte Cinema] Săn Combo Captain America",
        "news_description": "Địa điểm tất cả các rạp Lotte Cinema trên toàn quốc. Thời gian: Từ 25.04.2016",
        "type": 4,
        "date_add": "2016-04-21 17:10:02",
        "poster": "http://s3.img.edn.vn/123phim/2016/04/lotte-cinema-san-combo-captain-america-14612335165615.jpg",
        "banner": "http://s3.img.edn.vn/123phim/2016/04/lotte-cinema-san-combo-captain-america-14612336501269.jpg"
    }, {
        "news_id": 4158,
        "news_title": "[123Phim] Bom tấn ngày cá - Ưu đãi thả ga",
        "news_description": "Ngày Cá Tháng Tư, một lễ hội vui vẻ với những người tinh nghịch và hài hước sắp tới. Nhân ngày này, 123Phim hân hạnh mang đến chương trình khuyến mãi đặc biệt để bạn thêm vui.",
        "type": 4,
        "date_add": "2016-03-31 14:05:10",
        "poster": "http://s3.img.edn.vn/123phim/2016/03/123phim-bom-tan-ngay-ca-uu-dai-tha-ga-14594083443399.jpg",
        "banner": "http://s3.img.edn.vn/123phim/2016/03/123phim-bom-tan-ngay-ca-uu-dai-tha-ga-14594080645343.jpg"
    }, {
        "news_id": 4150,
        "news_title": "Nhận ngay 10.000 vé xem phim miễn phí tại BHD Star Vincom Lê Văn Việt",
        "news_description": "Nhân dịp khai trương cụm rạp mới tại trung tâm thương mại Vincom Plaza Lê Văn Việt(Quận 9), 123Phim phối hợp cùng với hệ thống BHD Star Cineplex để mang đến cho bạn 10, 000 vé xem phim hoàn toàn miễn phí.",
        "type": 4,
        "date_add": "2016-03-30 11:23:47",
        "poster": "http://s3.img.edn.vn/123phim/2016/03/c1bd20ec9f7bd252848b86a9a9e7602a.jpg",
        "banner": "http://s3.img.edn.vn/123phim/2016/03/nhan-ngay-10-000-ve-xem-phim-mien-phi-tai-bhd-star-vincom-le-van-viet-14593128247975.jpg"
    }, {
        "news_id": 4147,
        "news_title": "[Lotte Cinema] Giá Sốc Tháng Tư ",
        "news_description": "Áp dụng tại các rạp Lotte Cinema. Thời gian từ ngày 01/4/2016 đến 28/4/2016",
        "type": 4,
        "date_add": "2016-03-29 22:46:59",
        "poster": "http://s3.img.edn.vn/123phim/2016/03/lotte-cinema-gia-soc-thang-tu-14592664259207.jpg",
        "banner": "http://s3.img.edn.vn/123phim/2016/03/lotte-cinema-gia-soc-thang-tu-14592664473404.jpg"
    }]
}
```



# News Details
Request
```
GET [API_PATH]/data/news?news_id=4158
```

Response
```json
{
    "status": 1,
    "result": {
        "news_id": 4158,
        "news_title": "[123Phim] Bom t\u1ea5n ng\u00e0y c\u00e1 - \u01afu \u0111\u00e3i th\u1ea3 ga",
        "news_description": "Ng\u00e0y C\u00e1 Th\u00e1ng T\u01b0, m\u1ed9t l\u1ec5 h\u1ed9i vui v\u1ebb v\u1edbi nh\u1eefng ng\u01b0\u1eddi tinh ngh\u1ecbch v\u00e0 h\u00e0i h\u01b0\u1edbc s\u1eafp t\u1edbi. Nh\u00e2n ng\u00e0y n\u00e0y, 123Phim h\u00e2n h\u1ea1nh mang \u0111\u1ebfn ch\u01b0\u01a1ng tr\u00ecnh khuy\u1ebfn m\u00e3i \u0111\u1eb7c bi\u1ec7t \u0111\u1ec3 b\u1ea1n th\u00eam vui.",
        "type": 4,
        "date_add": "2016-03-31 14:05:10",
        "content": "<p dir=\"ltr\"><span>Ng&agrave;y C&aacute; Th&aacute;ng T\u01b0, m\u1ed9t l\u1ec5 h\u1ed9i vui v\u1ebb v\u1edbi nh\u1eefng ng\u01b0\u1eddi tinh ngh\u1ecbch v&agrave; h&agrave;i h\u01b0\u1edbc s\u1eafp t\u1edbi. Nh&acirc;n ng&agrave;y n&agrave;y, 123Phim h&acirc;n h\u1ea1nh mang \u0111\u1ebfn ch\u01b0\u01a1ng tr&igrave;nh khuy\u1ebfn m&atilde;i \u0111\u1eb7c bi\u1ec7t \u0111\u1ec3 b\u1ea1n th&ecirc;m vui.<\/span><\/p>\r\n<p><span><span>&nbsp;<\/span><\/span><\/p>\r\n<p dir=\"ltr\"><strong>1. Th\u1eddi gian di\u1ec5n ra ch\u01b0\u01a1ng tr&igrave;nh:<\/strong><span>&nbsp;00h &ndash; 23h59 ng&agrave;y 01\/04\/2016.<\/span><\/p>\r\n<p dir=\"ltr\"><strong>2. Th\u1ec3 l\u1ec7 ch\u01b0\u01a1ng tr&igrave;nh:<\/strong><\/p>\r\n<p dir=\"ltr\"><span>Nh\u1eadp m&atilde;&nbsp;<strong>#<\/strong><\/span><span><strong>4FOOL<\/strong>&nbsp;<\/span><span>\u0111\u1ec3 \u0111\u01b0\u1ee3c gi\u1ea3m ngay <\/span><strong>50,000\u0111<\/strong><span> khi mua t\u1eeb 02 v&eacute; xem phim tr\u1edf l&ecirc;n b\u1eb1ng \u1ee9ng d\u1ee5ng 123Phim.<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; Ch\u1ec9 &aacute;p d\u1ee5ng cho c&aacute;c su\u1ea5t chi\u1ebfu ng&agrave;y 01\/04 hi\u1ec3n th\u1ecb t\u1ea1i 123Phim.<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; &Aacute;p d\u1ee5ng khi xem phim t\u1ea1i h\u1ec7 th\u1ed1ng r\u1ea1p BHD, Galaxy v&agrave; Cinestar.<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; Kh&ocirc;ng &aacute;p d\u1ee5ng \u0111\u1ed3ng th\u1eddi v\u1edbi c&aacute;c khuy\u1ebfn m&atilde;i kh&aacute;c.<\/span><\/p>\r\n<p dir=\"ltr\"><strong>3. L\u01b0u &yacute;:<\/strong><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; M&atilde; bao g\u1ed3m d\u1ea5u #.<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; \u0110\u1ed1i v\u1edbi su\u1ea5t chi\u1ebfu c&aacute;c ng&agrave;y kh&aacute;c, m&atilde; <\/span><strong>#4FOOL&nbsp;<\/strong><span>kh&ocirc;ng c&oacute; hi\u1ec7u l\u1ef1c.<\/span><\/p>\r\n<p dir=\"ltr\"><strong>4. H\u01b0\u1edbng d\u1eabn nh\u1eadp m&atilde; &nbsp;&ldquo;#<\/strong><span><strong>4FOOL&rdquo;<\/strong>&nbsp;<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; T\u1ea3i app ngay t\u1ea1i \u0111&acirc;y&nbsp;<\/span><a href=\"http:\/\/www.123phim.vn\/app?utm_source=123phim&amp;utm_medium=promotion_detail&amp;utm_campaign=cathangtu\"><span>http:\/\/www.123phim.vn\/app<\/span><\/a><span>&nbsp;ho\u1eb7c t&igrave;m \u1ee9ng d\u1ee5ng123Phim tr&ecirc;n Store c\u1ee7a \u0111i\u1ec7n tho\u1ea1i (iOS, Android, Windows Phone).<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; Ch\u1ecdn phim, mua v&eacute; theo t\u1eebng b\u01b0\u1edbc tr&ecirc;n \u1ee9ng d\u1ee5ng, t\u1ea1i ph\u1ea7n thanh to&aacute;n nh\u1eadp&nbsp;<strong>#<\/strong><\/span><strong>4FOOL <\/strong><span>v&agrave;o &ocirc; M&atilde; Gi\u1ea3m Gi&aacute;.<\/span><\/p>\r\n<p dir=\"ltr\"><span>- &nbsp; &nbsp; Xem h&igrave;nh \u1ea3nh h\u01b0\u1edbng d\u1eabn c\u1ee5 th\u1ec3, click&nbsp;<\/span><a href=\"http:\/\/www.123phim.vn\/e-voucher\"><span>t\u1ea1i \u0111&acirc;y<\/span><\/a><span>.<\/span><\/p>\r\n<p dir=\"ltr\"><span>B\u1ea1n s\u1ebd ch\u1ecdn g&igrave;? Tranh th\u1ee7 xem l\u1ea1i <\/span><a href=\"http:\/\/www.123phim.vn\/phim\/804-batman-v-superman-dawn-of-justice.html\"><span>Batman v Superman<\/span><\/a><span> hay b\u1eaft \u0111&uacute;ng trend, vui \u0111&uacute;ng nh\u1ecbp v\u1edbi phim<\/span>&nbsp;<a href=\"http:\/\/www.123phim.vn\/phim\/1072-lich-chieu-nhan-luc-sieu-nhien-midnight-special.html\">Midnight Special<\/a>&nbsp;s\u1ebd ra r\u1ea1p v&agrave;o tu\u1ea7n n&agrave;y?<\/p>\r\n<p dir=\"ltr\"><span>Nhanh ch&oacute;ng c\u1ea7m \u0111i\u1ec7n tho\u1ea1i l&ecirc;n t\u1ea3i app, \u0111\u1eb7t v&eacute; v&agrave; r\u1ee7 ngay b\u1ea1n b&egrave; tham gia ch\u01b0\u01a1ng tr&igrave;nh n&agrave;y th&ocirc;i!<\/span><\/p>\r\n<p style=\"text-align: right;\" dir=\"ltr\"><strong>123Phim<\/strong><\/p>",
        "poster": "http:\/\/s3.img.edn.vn\/123phim\/2016\/03\/123phim-bom-tan-ngay-ca-uu-dai-tha-ga-14594083443399.jpg",
        "banner": "http:\/\/s3.img.edn.vn\/123phim\/2016\/03\/123phim-bom-tan-ngay-ca-uu-dai-tha-ga-14594080645343.jpg"
    }
}
```


