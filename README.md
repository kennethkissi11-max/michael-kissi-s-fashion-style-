<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Michael Kissi | Fashion Dress Styles</title>
<meta name="description" content="Explore casual, formal, traditional, and street fashion styles by Michael Kissi.">

<style>
html { scroll-behavior: smooth; }

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

/* HEADER */
header {
    background-color: #111;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

/* FILTER BUTTONS */
.filters {
    text-align: center;
    margin: 30px 0;
}

.filters button {
    padding: 10px 20px;
    margin: 5px;
    border: none;
    background: #111;
    color: white;
    border-radius: 20px;
    cursor: pointer;
}

.filters button:hover {
    background: #e91e63;
}

/* CONTENT */
.container {
    padding: 20px;
}

.section {
    background-color: white;
    margin-bottom: 40px;
    padding: 25px;
    border-radius: 6px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

/* ITEM */
.item {
    display: flex;
    flex-direction: column;
    cursor: pointer;
}

.item img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 6px;
}

/* CAPTION UNDER IMAGE */
.item span {
    margin-top: 8px;
    padding: 6px;
    background: #111;
    color: white;
    text-align: center;
    border-radius: 0 0 6px 6px;
    font-size: 14px;
}

/* LIGHTBOX */
.lightbox {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.8);
    display: none;
    align-items: center;
    justify-content: center;
}

.lightbox img {
    max-width: 90%;
    max-height: 90%;
}

/* FOOTER */
footer {
    background-color: #111;
    color: white;
    text-align: center;
    padding: 15px;
}

/* RESPONSIVE */
@media (max-width: 900px) {
    .gallery {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 500px) {
    .gallery {
        grid-template-columns: 1fr;
    }
}
</style>
</head>

<body>

<header>
    <h1>MICHAEL KISSI'S FASHION DRESS STYLE</h1>
    <p>Explore different dressing styles</p>
</header>

<div class="container">

<div class="filters">
    <button onclick="filterItems('all')">All</button>
    <button onclick="filterItems('casual')">Casual</button>
    <button onclick="filterItems('formal')">Formal</button>
    <button onclick="filterItems('traditional')">Traditional</button>
    <button onclick="filterItems('street')">Street</button>
</div>

<div class="filters">
      <button onclick="filterItems('male')">male</botton>
      <button onclick="filterItems('female')">female</botton>
</div>

<section class="section">
<div class="gallery">

<!-- CASUAL -->
<div class="item casual female">
    <img src=https://upfrica-production.s3.eu-west-2.amazonaws.com/direct_uploads/f0a01caf-d17d-4209-9541-b973b76867d3 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.etsystatic.com/37621895/r/il/18bcf7/4622946676/il_fullxfull.4622946676_pv4t.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://ae01.alicdn.com/kf/S263902aaf8474a8dac186c9227cc6af7v.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/736x/60/ae/88/60ae8812c46283841b2958c75e801e27.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/236x/fe/14/8e/fe148eb727c58063badf679c9c186de5.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://gh.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/82/1738292/1.jpg?5238 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://gh.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/48/1956031/1.jpg?0558 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPIBANCaJrdHRszEIdrOfhHiyLd7-MYeB3pTWgHeSNcg&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://m.media-amazon.com/images/I/61sbcsUG5lL._AC_UY1000_.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.etsystatic.com/40388244/r/il/f9af46/7171327834/il_300x300.7171327834_qpd2.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfWVyMxfiZxN_PaCUZh2NowcCBkVVKDVxeNdOYnairpg&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDgX4cgj0II6SNQYmvmxipBw9-TB3poMhtl4GClUGAhw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfCJbZ7wKQqt-_G-PpWc9wNc9z677-N8L0Mi0DR_0sGA&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeDl4FcnD6037_fpuJ9fn6bbtMm25bAgwbciskv563Kw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTabYJVCrDQOTmwIM-oVnSiRxGtCZYgBGr6GYf1jvUe3A&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVRITiFZDmKL9O6QvDwh3fBaZQUTJi7xTrOqankTxevw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/564x/ea/80/12/ea8012c93bd13e13cd871ed24f98798f.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i0.wp.com/clipkulture.com/wp-content/uploads/2022/06/il_794xN.3306061349_71po.webp?ssl=1 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://img.kwcdn.com/product/fancy/0902a569-51d5-4bd5-b113-5013abbdeaec.jpg?imageMogr2/auto-orient%7CimageView2/2/w/800/q/70/format/webp alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfhwXkhCflMsFWf4fP753GdSA3bD1b3sNLQjy8wDTekw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://m.media-amazon.com/images/I/61S7iSvmhYL._AC_SL1024_.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGhz54sLBau2BxQOwaOZzzoQ1Q5QsMNkEq4w&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStNgp5eBfSAlTDzI5_-24qvKxNRUnkfUAXfaygVVe9tQ&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.etsystatic.com/29168401/r/il/b7b174/3471233578/il_570xN.3471233578_bte2.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/originals/35/6b/f0/356bf0cb5bcf9ae4729709eb95a4e411.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/736x/d7/38/4f/d7384f218ca8805b229bd30ed88037d1.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://pictures-ghana.jijistatic.net/50758403_NjIwLTkzMC01MGZiNTkyOTU2.webp alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual female">
    <img src=https://assets.vogue.com/photos/64c817ec9a401f430c2a3271/master/w_1600%2Cc_limit/GettyImages-1497245159.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://africablooms.com/wp-content/uploads/2019/03/Ghana-Wedding-Kente-White-Suit-AFRICA-BLOOMS.jpg alt="Casual Look">
     <span>Casual Look</span>
</div>

<div class="item casual female"> 
    <img src=https://gh.jumia.is/unsafe/fit-in/500x500/filters:fill(white)/product/28/3870992/1.jpg?8834 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0AeJnQdjHw9mQCEwyePB3uEEy5Hseroz-Ww&s alt="Casual Look">
    <span>Casual Look</span>
</div> 

<div class="item casual female">
     <img src=https://wearghana.com/wp-content/uploads/2023/11/Wear-Ghana_s-Website-Update-526.jpg alt="Normal wear">
     <span>Normal wear</span>
</div>

<div class="item casual female">
    <img src=https://i0.wp.com/esafric.com/wp-content/uploads/2018/03/2018-Print-Casual-Maxi-Dress-Women-Back-Bandage-Halter-Club-Party-Dresses-Summer-Long-Sexy-Dress.jpg?fit=805%2C1024&ssl=1 alt="Product Image">
    <span>Ghana wear</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/736x/29/1f/bc/291fbc7725f3f80dbef05f30993923b2.jpg alt="Casual Outfit">
    <span>Casual Outfit</span>
</div>

<div class="item casual female">
    <img src=https://pictures-ghana.jijistatic.net/56219312_MzAwLTMwMC05YzE3ZGEyNmE1.webp alt="Casual Outfit">
     <span>Casual Outfit</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnCXoVfiUu9fFIqQ8_GdPpVaKIe9b2Hqa8Mg&s alt="Everyday Casual">
    <span>Everyday Casual</span>
</div>

<div class="item casual female">
    <img src=https://i.pinimg.com/736x/7a/bd/cd/7abdcd67be093119f6985e2cdc23551d.jpg alt="Everyday Casual">
    <span>Everyday Casual</span>
    </div>

<div class="item casual male">
    <img src=https://wearghana.com/wp-content/uploads/2023/12/Copy-of-Wear-Ghana_s-Website-Update-508-1.jpg alt="Normal wear">
    <span>Normal wear</span>
</div>

<!-- FORMAL -->
<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRKPrPi0LpgCD2trQiyiOVJ42u-v8gp8ZxHCw&s alt="Formal Suit">
    <span>Formal Suit</span>
</div>

<div class="item formal male">
    <img src=https://images.ctfassets.net/371ugtyffwio/18ljFkvVMzxNLAnqpQMWm1/4399f825ae231d21089ef215a37b5510/formal-wear-m.jpg?w=1620&q=85&fm=webp alt="Office Wear">
    <span>Office Wear</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGDYVXL0o6eDjxyvrJRBy8hXD37dyXwcBFofTleXL7Iw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJvwXJ6V9BYpq-FCsBQ3-_XHax8xmBV9XsQ4pg1R75rQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://cdn.gentlemansguru.com/wp-content/uploads/2018/11/Mens-Tuxedos-Tuxedo-Jackets-from-Gentlemansguru.com_-e1543515088481.jpg?w=765&q=85&sharp=0.3&output=webp alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQCULlXP-4067a8pJZGn0zJzLNKKj0qz3NqGUycyXtosQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://i.pinimg.com/736x/f1/69/77/f169773e34e2d590cd87173be605ef18.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTnCP_HQv1yrFIp6N1C3TDBDT1hZoI9d7i7ZHh2d3bsEw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhNBnk2KEwd7rx1CvDIU-u2ZhlNwuYtwgOsg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6uqlVayfSBgp04tCAxIsBnsWPihquFaG7Q43aRN85pA&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrto7sSNenZNsGIL2Xi5YuY8VX5mIJ91DcoiteaG-2eQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvwMfyYPI885iTCD0sMVcTwCraDbOwh6nCWbB3mkKm9w&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://cdn.shopify.com/s/files/1/0029/1887/5193/files/classic_colors_480x480.jpg?v=1595431667 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1izGjJDx9mM-lvr3YDNeSBPHi_G60_odbILXPIYdFlQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://i.pinimg.com/236x/51/35/38/513538ab1425156cb99818eb9621a31b.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS22VAJj6p0BEznUTOTjeRI4-S858UVqFmnwOqCReegDw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://m.media-amazon.com/images/I/61vvCbxtuTL._AC_UF894,1000_QL80_.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSD6W5mI_is5QVcN2FzHo7OK2L6BNuwrGCxYrIgLuLTTg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://image.made-in-china.com/2f0j00tqIcOGTRsboV/Women-Gender-Business-Product-Type-Formal-Clothes-for-Office-Tailor-Made-fashion-Women-Skirt-Suit-Lady-Formal-Suit.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-PgMCCzNkqolD9UtR9LCxh63CPLT1al672m15DVAuTA&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://fithubfashion.com/cdn/shop/files/23_may8753_551b15b8-d71d-465e-8cd9-3eb324ecf11e.jpg?v=1755683521&width=1445 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqlJfahc0mqJ1pL5nRSNt937H24JOojWGBnJr6tFVZVg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.bewakoof.com/blog/wp-content/uploads/2023/03/17.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://images-cdn.ubuy.co.in/6671fff67b80b51895193802-elegant-fairy-dresses-women-casual-party.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.westside.com/cdn/shop/articles/formal_wear_for_women.jpg?v=1662636789 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.pluchdesigns.com/cdn/shop/files/A317AC8B-E390-4CE2-8FE8-077DE5541E00.png?v=1756125219&width=500 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://parade.com/.image/w_3840,q_auto:good,c_limit/MTk5NjU5MjEyNDEyODIzMTY4/Amazon_semi-formal-attire-floral-blouse.jpg?arena_f_auto alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKWpCYY-Z-IvsoCGRZipU6I7kiovjQN6-e5vyONT-RLA&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHH1eTxm0cOgrRQnY7qiW6sFr7Q7MiKZQRTXTwLJZdTg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://i5.walmartimages.com/seo/Semi-Formal-Dress-for-Women-TIANEK-V-Neck-Floral-Shape-Ball-Graduation-Dress-Maxi-Long-Dress_55baafb2-f843-4948-97b1-81ade0d71152.274fbe3ccdae4028e9508196e78d3531.jpeg?odnHeight=768&odnWidth=768&odnBg=FFFFFF alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://images-na.ssl-images-amazon.com/images/I/61IK7QAidmL._UL500_.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSrGnFETH0_sFxSBo1Ofxh5YDRhaX520X1BVAGC_UlCVg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBQDXPmyQOCwtUNmJjk4LYm5tlFjwBeiUNJFlQqvDjyw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://gh.jumia.is/unsafe/fit-in/500x500/filters:fill(white)/product/12/066148/2.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://i5.walmartimages.com/seo/Women-s-Dress-Office-Dress-3-4-Sleeves-Pleated-Tie-Plus-Size-Dress-Leisure-Classic-Ladies-Chic-Dresses-Summer-Spring_524f8eef-ecfc-4b62-8522-43483ff8aae6.8d8d6b1d9177cd85f7bf8cf5bc81139e.jpeg?odnHeight=768&odnWidth=768&odnBg=FFFFFFhttps://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThZpM9_3cG9Dnm5UTnOuakSOJE1OYGKEzCbSRpTBDXkcsS3PUj1nwqT6o&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://cdn.shopify.com/s/files/1/0486/0634/7416/products/stylish_jacket_with_pockets_l1.jpg?v=1746683865 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.houseoftailors.ae/assets/images/images/formal-women/women-formal-suits-1.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<!-- TRADITIONAL -->
<div class="item traditional male">
    <img src=https://africablooms.com/wp-content/uploads/2019/03/Ghana-Wedding-Kente-Black-Suit-AFRICA-BLOOMS.jpg alt="Traditional Wear">
    <span>Traditional Wear</span>
</div>

<div class="item traditional male">
    <img src=https://www.mgkente.com/cdn/shop/files/4e85016ebb7a416adfb1dcc013a7b2f6-resized.jpg?v=1697319674&width=1946 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://vondeeworld.com/wp-content/uploads/2025/01/VondeeWorld-Northern-Ghana-Smock-for-Men-8a-430x602.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://vondeeworld.com/wp-content/uploads/2025/01/1acj-Vondeeworld-African-Smock-men.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://img.freepik.com/free-photo/side-view-man-wearing-native-attire_23-2150397430.jpg?semt=ais_hybrid&w=740&q=80 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://s.alicdn.com/@sc04/kf/H555dbb3b698c4cbb924520536400ed01a/Yibaoli-Factory-Supply-High-Quality-Fashion-Clothing-Ankara-Cotton-Traditional-African-Clothes-for-Men-African-Suit.jpg_300x300.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://ishafrica.com/wp-content/uploads/2022/12/Olu-Short-Sleeve-Mandarin-Button-Up-African-Print-Shirt-Black-Brown-Geometric.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://s.alicdn.com/@sc04/kf/Hb3d0ab10291642b9a05491c8757a9f20s/High-Quality-Polyester-Cotton-Mens-Fashion-Design-Africa-Traditional-Ethnic-Clothing-African-Dashiki-Shirts-African-Clothing.jpg_300x300.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://i.pinimg.com/736x/92/24/b5/9224b57605c07366e39211bdc284f0c7.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://i0.wp.com/clipkulture.com/wp-content/uploads/2021/05/13-45-48-173533678_294582045596910_5367122396622286927_n.jpg?fit=1080%2C1350&ssl=1 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://www.africablooms.com/wp-content/uploads/2019/02/Latest-African-Wear-for-Men-%E2%80%93-Dashiki-Shirt-for-Men-%E2%80%93-Ghana-Kente-Shirt-AFRICA-BLOOMS.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://danddclothing.com/cdn/shop/articles/Kente_Church_Dress_For_Men_7d510f77-3f6d-468a-9f08-372fffeb5dbc_1400x.jpg?v=1624374644 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://i5.walmartimages.com/seo/BintaRealWax-Ankara-African-Dresses-Women-Traditional-Ghana-Elegant-Short-Sleeve-High-Waist-African-Print-Maxi-Dress-Africa-Clothing-Wedding-WY3629_d6139b31-afaa-45d5-9a39-86916cc74773.c0e28c1177e1a79e850ceef9dea48d51.jpeg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://karentinoboutique.com/cdn/shop/files/Africanprinteveningdress35A_2048x.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://i.etsystatic.com/17679582/r/il/561621/5100694146/il_fullxfull.5100694146_g2gg.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://img.kwcdn.com/product/fancy/53402367-aefd-44ef-bdfd-05575accfec9.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSG6SNctOBrKmk5CzVErJ2HjsrrNzoYU5RwdBlpAMltR_HyeUHc_oAXhic&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEcReBCUmxaZpjZAt5YmPPHbr9b6EtBt39F1DzEU_rKQ&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfjt8SOJPPrEug7Ya_G4n8wYzxFkULkX6BBDxELfdJDg&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://cdn.globalso.com/africlife/African-clothing-dashiki.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLyARGz_7gIkbQjh95ARszJmcSIY6h17Zf0m9H_rHkyg&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female ">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKWQQilSFpK-hOkhV3mflz2riiUFVCBYDLPfSETqMCyw&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSR4LskOdrG5aUlRo3Wdc7SYM6AtCb50v4aIiPgwXHDnw&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXVl3XqVKT87SgVxtr-LyGltTJMZGaV-Wq5tU-p_pRNg&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://i5.walmartimages.com/seo/BintaRealWax-Ankara-African-Dresses-Women-Traditional-Ghana-Elegant-Short-Sleeve-High-Waist-Print-Maxi-Dress-Africa-Clothing-Wedding-WY3629_3de33c86-c7e9-40db-b93c-0e6ba6d0fdc6.d1899058b2148bcf42f1d97c9cc4db28.jpeg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTukoja6gXpzVfjQzP-b-nJQ7-cF7Bi3zTkRLoqRNHJGA&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRHUG0QESI9Rf-RfcIux4GyAHs2zsWbhmNlCcHmzjKhZA&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQQf-2QRtqTqaWhwFsC-hqbppsKuG8QG5ApiZQSTtsVSg&s alt="African Style">
    <span>African Style</span>
</div>

<!-- STREET -->
<div class="item street male">
    <img src=https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2024%2F06%2F17%2Fmilan-fashion-week-mens-ss25-street-style-026.jpg?q=75&w=800&cbr=1&fit=max alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://www.alanic.clothing/wp-content/uploads/2021/04/men-fashion-casual-streetwear-t-shirt.jpg alt="Urban Wear">
    <span>Urban Wear</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlz1j6Js1jy5QOfjJfeDjfJhxXhti8voXOz_FN_RibEA&s alt="Modern Street">
    <span>Modern Street</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzpsnOFXBxHB5GQG8UttEo4BRXdtOLZRrO18MCm7GE-Q&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://www.alanic.clothing/wp-content/uploads/2021/04/gray-casual-streetwear-t-Shirt.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://cdn.karmaloopassets.com/media//gene-cms/d/r/dropdown__400x400.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://streetwear.store/cdn/shop/files/streetwear-pants_300x.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://techwear-outfits.com/cdn/shop/files/streetwear-black-and-white-pants-techwear-334.webp?v=1692252521&width=720 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT54N3kpXRMHvW95okQ43bCEb-K2ee2FOmJj-KHbuN_WQ&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://scene7.zumiez.com/is/image/zumiez/397120-US alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://scene7.zumiez.ca/is/image/zumiez/189804-CA alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTymCvCYUyw2tTZAqp11WEcGpqQuqZoqs_cvZfB58uGlA&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRfGr5tI0aHcJogMYHcr1n0tTQNwP24OPT3FO-UKSowNQ&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTTKFClPkPh1GyNbVC-PbpaB4fC2CLIRZZpO8gkN9kCcA&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ62SO8QFbS0ULzfw6tP2a4jYIdiUC9eS4yqFDetZ10lw&shttps://cyber-techwear.com/cdn/shop/articles/product-image-1700778219.jpg?v=1719539357 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTI5vaFOsOBVvUDILrUVnybIqLbecSxDiDpLJ0W0G_5zw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://thestreetsofseoul.com/cdn/shop/products/Cropped-Faux-Leather-Jacket-thestreetsofseoul-korean-street-style-minimal-streetwear-k-style-kstyle-mens-affordable-clothing-2.jpg?v=1655047850&width=1920 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://japanese-temple.com/cdn/shop/products/japanese-streetwear-pant-29605088821408_2000x.jpg?v=1628174705 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://streetwear.com.ua/img/p/full/100/8045100a.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTF-XRPWoZD1jqB4TX8A7kESmOaEWOPnF97Hh5j7pXn1g&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://www.moderngentlemanmagazine.com/wp-content/uploads/2024/10/Shearling-Swagger-650x813.jpeg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://www.bellanaijastyle.com/wp-content/uploads/2023/09/22A0776-Edit-scaled.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street female">
    <img src=https://i.pinimg.com/736x/45/1d/32/451d32ae0ca621844a602e54c4568b99.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKaRsiSgxgsrbM4jRKY4U0WJddb-vGzGIb9kMuJjfkzA&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://www.yourcoffeebreak.co.uk/wp-content/uploads/d9a65be8051b1c25035c63728aea888f.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQsxv46KTN0jD2kJp0BHQHKtkg61l6bwOltYRVdX7ih0A&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://www.yourcoffeebreak.co.uk/wp-content/uploads/073b458b67e4348f1d2463fe4cf09bba.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUMBFV4VtYRDEx4clcte4KSqGFQE03Zba7L4RpGQLpsQ&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://cdn.shopify.com/s/files/1/1023/3455/files/02054108-YE282_womens_0010.jpg?v=1753746607&width=500 alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://img.businessoffashion.com/resizer/v2/UTQ7H5L2G5BWRMNIFMVYZKEQVI.jpg?auth=b1ee936a29eb4b22c751fb714ddfb833c69913067530519ae37307f267acd979&width=1440 alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://img.businessoffashion.com/resizer/v2/UTQ7H5L2G5BWRMNIFMVYZKEQVI.jpg?auth=b1ee936a29eb4b22c751fb714ddfb833c69913067530519ae37307f267acd979&width=1440https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeayeTj9W_-cIBvN8ny8Yzk9wzCe5K2Zm3D611oW54Bw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://fashionista.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cq_auto:good%2Cw_1200/MTY1Mzc5MzE4NTYwNTk3NDA5/aleali-may-streetwear-1.png alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkb6i6DjNedOWgd4GtVujMnmUpsLwUiZ9JeaK26-ShOg&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fwp-content%2Fblogs.dir%2F6%2Ffiles%2F2018%2F10%2Fhypefest-street-style-new-york-city-23.jpg?q=75&w=800&cbr=1&fit=max alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://img.tobi.com/product_images/sm/1/medium-wash-devin-denim-high-rise-shorts.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSjQqgtuQWovAbIlbZNo085p7h9S6pUWj5bq9I2OCMq5g&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRaW-_Ipi6qfFjzccYXCjkks-_K24DDfq-NRDme9Y9o_A&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwgOb-c_-C9eorxy3UF5nDyP4yGO1bB2SbgUQzPY47Vw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTatFfP2LlOgtJCL6Yge5WDmkKKNAPBa8E7zwyd0fnS3w&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://cdn-img.prettylittlething.com/1/a/f/1/1af1887f6246d7402f8309e21797c57f589b3d78_cnj9270_1.jpg?imwidth=600 alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUhV1Lj1WNG7z0y_aiyJVQFtMa9QiFRI53QcdxMkviYw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREXexrLrFFgOHF1sbcumCUWR4VpJBJWEPwXhdRSLIaWA&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRBbkVUuIvaC6alDUt82wqjS2ms3ZnHUzvrCMY8tz6rqw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQH_KFTksv3zg-Vzi4H4lKR80zqNbqZrJ8Xb7-7xc-UAw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://s.alicdn.com/@sc04/kf/H7da2871d29e04fbc9ee8304555bc09bbT/G01656C-Winter-New-Fashion-Ribbing-Woman-2-Piece-Set-Outfit-Solid-Color-Skiny-Pants-Female-Streetwear.png_300x300.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTgdCguTyT38WmuBX86qi9XBjqBu3JLkupLdI2G7uLSkw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbbIjRSBOSDyFItbwFIpOCP4ss6pA5ovC0ZonmyYvPyw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://lewkin.com/cdn/shop/collections/col_street.jpg?crop=center&height=500&v=1702451622&width=600 alt="Street Fashion">
    <span>Street Fashion</span>
</div>


<div class="item street female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJKZZOQrsbFs3pooyvUUA47FRKq5cA6X6cEgY0FLVmog&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

</div>
</section>
</div>

<div class="lightbox" onclick="this.style.display='none'">
    <img id="lightboxImg">
</div>

<footer>
    <p>&copy; 2026 Michael Kissi. All Rights Reserved.</p>
</footer>

<script>
const items = document.querySelectorAll('.item');
const lightbox = document.querySelector('.lightbox');
const lightboxImg = document.getElementById('lightboxImg');

let activeStyle = 'all';
let activeGender = 'all';

/* LIGHTBOX */
items.forEach(item => {
    item.addEventListener('click', () => {
        lightbox.style.display = 'flex';
        lightboxImg.src = item.querySelector('img').src;
    });
});

/* FILTER FUNCTION */
function filterItems(type) {

    // Detect if filter is style or gender
    if (['casual', 'formal', 'traditional', 'street', 'all'].includes(type)) {
        activeStyle = type;
    } else if (['male', 'female'].includes(type)) {
        activeGender = type;
    }

    items.forEach(item => {
        const matchStyle =
            activeStyle === 'all' || item.classList.contains(activeStyle);

        const matchGender =
            activeGender === 'all' || item.classList.contains(activeGender);

        item.style.display = (matchStyle && matchGender) ? 'flex' : 'none';
    });
}
</script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Michael Kissi | Fashion Dress Styles</title>
<meta name="description" content="Explore casual, formal, traditional, and street fashion styles by Michael Kissi.">

<style>
html { scroll-behavior: smooth; }

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

/* HEADER */
header {
    background-color: #111;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

/* FILTER BUTTONS */
.filters {
    text-align: center;
    margin: 30px 0;
}

.filters button {
    padding: 10px 20px;
    margin: 5px;
    border: none;
    background: #111;
    color: white;
    border-radius: 20px;
    cursor: pointer;
}

.filters button:hover {
    background: #e91e63;
}

/* CONTENT */
.container {
    padding: 20px;
}

.section {
    background-color: white;
    margin-bottom: 40px;
    padding: 25px;
    border-radius: 6px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

/* ITEM */
.item {
    display: flex;
    flex-direction: column;
    cursor: pointer;
}

.item img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 6px;
}

/* CAPTION UNDER IMAGE */
.item span {
    margin-top: 8px;
    padding: 6px;
    background: #111;
    color: white;
    text-align: center;
    border-radius: 0 0 6px 6px;
    font-size: 14px;
}

/* LIGHTBOX */
.lightbox {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.8);
    display: none;
    align-items: center;
    justify-content: center;
}

.lightbox img {
    max-width: 90%;
    max-height: 90%;
}

/* FOOTER */
footer {
    background-color: #111;
    color: white;
    text-align: center;
    padding: 15px;
}

/* RESPONSIVE */
@media (max-width: 900px) {
    .gallery {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 500px) {
    .gallery {
        grid-template-columns: 1fr;
    }
}
</style>
</head>

<body>

<header>
    <h1>MICHAEL KISSI'S FASHION DRESS STYLE</h1>
    <p>Explore different dressing styles</p>
</header>

<div class="container">

<div class="filters">
    <button onclick="filterItems('all')">All</button>
    <button onclick="filterItems('casual')">Casual</button>
    <button onclick="filterItems('formal')">Formal</button>
    <button onclick="filterItems('traditional')">Traditional</button>
    <button onclick="filterItems('street')">Street</button>
</div>

<div class="filters">
      <button onclick="filterItems('male')">male</botton>
      <button onclick="filterItems('female')">female</botton>
</div>

<section class="section">
<div class="gallery">

<!-- CASUAL -->
<div class="item casual female">
    <img src=https://upfrica-production.s3.eu-west-2.amazonaws.com/direct_uploads/f0a01caf-d17d-4209-9541-b973b76867d3 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.etsystatic.com/37621895/r/il/18bcf7/4622946676/il_fullxfull.4622946676_pv4t.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://ae01.alicdn.com/kf/S263902aaf8474a8dac186c9227cc6af7v.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/736x/60/ae/88/60ae8812c46283841b2958c75e801e27.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/236x/fe/14/8e/fe148eb727c58063badf679c9c186de5.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://gh.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/82/1738292/1.jpg?5238 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://gh.jumia.is/unsafe/fit-in/300x300/filters:fill(white)/product/48/1956031/1.jpg?0558 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPIBANCaJrdHRszEIdrOfhHiyLd7-MYeB3pTWgHeSNcg&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://m.media-amazon.com/images/I/61sbcsUG5lL._AC_UY1000_.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.etsystatic.com/40388244/r/il/f9af46/7171327834/il_300x300.7171327834_qpd2.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfWVyMxfiZxN_PaCUZh2NowcCBkVVKDVxeNdOYnairpg&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDgX4cgj0II6SNQYmvmxipBw9-TB3poMhtl4GClUGAhw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfCJbZ7wKQqt-_G-PpWc9wNc9z677-N8L0Mi0DR_0sGA&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeDl4FcnD6037_fpuJ9fn6bbtMm25bAgwbciskv563Kw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTabYJVCrDQOTmwIM-oVnSiRxGtCZYgBGr6GYf1jvUe3A&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVRITiFZDmKL9O6QvDwh3fBaZQUTJi7xTrOqankTxevw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/564x/ea/80/12/ea8012c93bd13e13cd871ed24f98798f.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i0.wp.com/clipkulture.com/wp-content/uploads/2022/06/il_794xN.3306061349_71po.webp?ssl=1 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://img.kwcdn.com/product/fancy/0902a569-51d5-4bd5-b113-5013abbdeaec.jpg?imageMogr2/auto-orient%7CimageView2/2/w/800/q/70/format/webp alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfhwXkhCflMsFWf4fP753GdSA3bD1b3sNLQjy8wDTekw&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://m.media-amazon.com/images/I/61S7iSvmhYL._AC_SL1024_.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGhz54sLBau2BxQOwaOZzzoQ1Q5QsMNkEq4w&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStNgp5eBfSAlTDzI5_-24qvKxNRUnkfUAXfaygVVe9tQ&s alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.etsystatic.com/29168401/r/il/b7b174/3471233578/il_570xN.3471233578_bte2.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/originals/35/6b/f0/356bf0cb5bcf9ae4729709eb95a4e411.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/736x/d7/38/4f/d7384f218ca8805b229bd30ed88037d1.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://pictures-ghana.jijistatic.net/50758403_NjIwLTkzMC01MGZiNTkyOTU2.webp alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual female">
    <img src=https://assets.vogue.com/photos/64c817ec9a401f430c2a3271/master/w_1600%2Cc_limit/GettyImages-1497245159.jpg alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual male">
    <img src=https://africablooms.com/wp-content/uploads/2019/03/Ghana-Wedding-Kente-White-Suit-AFRICA-BLOOMS.jpg alt="Casual Look">
     <span>Casual Look</span>
</div>

<div class="item casual female"> 
    <img src=https://gh.jumia.is/unsafe/fit-in/500x500/filters:fill(white)/product/28/3870992/1.jpg?8834 alt="Casual Look">
    <span>Casual Look</span>
</div>

<div class="item casual female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0AeJnQdjHw9mQCEwyePB3uEEy5Hseroz-Ww&s alt="Casual Look">
    <span>Casual Look</span>
</div> 

<div class="item casual female">
     <img src=https://wearghana.com/wp-content/uploads/2023/11/Wear-Ghana_s-Website-Update-526.jpg alt="Normal wear">
     <span>Normal wear</span>
</div>

<div class="item casual female">
    <img src=https://i0.wp.com/esafric.com/wp-content/uploads/2018/03/2018-Print-Casual-Maxi-Dress-Women-Back-Bandage-Halter-Club-Party-Dresses-Summer-Long-Sexy-Dress.jpg?fit=805%2C1024&ssl=1 alt="Product Image">
    <span>Ghana wear</span>
</div>

<div class="item casual male">
    <img src=https://i.pinimg.com/736x/29/1f/bc/291fbc7725f3f80dbef05f30993923b2.jpg alt="Casual Outfit">
    <span>Casual Outfit</span>
</div>

<div class="item casual female">
    <img src=https://pictures-ghana.jijistatic.net/56219312_MzAwLTMwMC05YzE3ZGEyNmE1.webp alt="Casual Outfit">
     <span>Casual Outfit</span>
</div>

<div class="item casual male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnCXoVfiUu9fFIqQ8_GdPpVaKIe9b2Hqa8Mg&s alt="Everyday Casual">
    <span>Everyday Casual</span>
</div>

<div class="item casual female">
    <img src=https://i.pinimg.com/736x/7a/bd/cd/7abdcd67be093119f6985e2cdc23551d.jpg alt="Everyday Casual">
    <span>Everyday Casual</span>
    </div>

<div class="item casual male">
    <img src=https://wearghana.com/wp-content/uploads/2023/12/Copy-of-Wear-Ghana_s-Website-Update-508-1.jpg alt="Normal wear">
    <span>Normal wear</span>
</div>

<!-- FORMAL -->
<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRKPrPi0LpgCD2trQiyiOVJ42u-v8gp8ZxHCw&s alt="Formal Suit">
    <span>Formal Suit</span>
</div>

<div class="item formal male">
    <img src=https://images.ctfassets.net/371ugtyffwio/18ljFkvVMzxNLAnqpQMWm1/4399f825ae231d21089ef215a37b5510/formal-wear-m.jpg?w=1620&q=85&fm=webp alt="Office Wear">
    <span>Office Wear</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGDYVXL0o6eDjxyvrJRBy8hXD37dyXwcBFofTleXL7Iw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJvwXJ6V9BYpq-FCsBQ3-_XHax8xmBV9XsQ4pg1R75rQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://cdn.gentlemansguru.com/wp-content/uploads/2018/11/Mens-Tuxedos-Tuxedo-Jackets-from-Gentlemansguru.com_-e1543515088481.jpg?w=765&q=85&sharp=0.3&output=webp alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQCULlXP-4067a8pJZGn0zJzLNKKj0qz3NqGUycyXtosQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://i.pinimg.com/736x/f1/69/77/f169773e34e2d590cd87173be605ef18.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTnCP_HQv1yrFIp6N1C3TDBDT1hZoI9d7i7ZHh2d3bsEw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhNBnk2KEwd7rx1CvDIU-u2ZhlNwuYtwgOsg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6uqlVayfSBgp04tCAxIsBnsWPihquFaG7Q43aRN85pA&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrto7sSNenZNsGIL2Xi5YuY8VX5mIJ91DcoiteaG-2eQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvwMfyYPI885iTCD0sMVcTwCraDbOwh6nCWbB3mkKm9w&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://cdn.shopify.com/s/files/1/0029/1887/5193/files/classic_colors_480x480.jpg?v=1595431667 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1izGjJDx9mM-lvr3YDNeSBPHi_G60_odbILXPIYdFlQ&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://i.pinimg.com/236x/51/35/38/513538ab1425156cb99818eb9621a31b.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS22VAJj6p0BEznUTOTjeRI4-S858UVqFmnwOqCReegDw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://m.media-amazon.com/images/I/61vvCbxtuTL._AC_UF894,1000_QL80_.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSD6W5mI_is5QVcN2FzHo7OK2L6BNuwrGCxYrIgLuLTTg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://image.made-in-china.com/2f0j00tqIcOGTRsboV/Women-Gender-Business-Product-Type-Formal-Clothes-for-Office-Tailor-Made-fashion-Women-Skirt-Suit-Lady-Formal-Suit.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-PgMCCzNkqolD9UtR9LCxh63CPLT1al672m15DVAuTA&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://fithubfashion.com/cdn/shop/files/23_may8753_551b15b8-d71d-465e-8cd9-3eb324ecf11e.jpg?v=1755683521&width=1445 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqlJfahc0mqJ1pL5nRSNt937H24JOojWGBnJr6tFVZVg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.bewakoof.com/blog/wp-content/uploads/2023/03/17.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://images-cdn.ubuy.co.in/6671fff67b80b51895193802-elegant-fairy-dresses-women-casual-party.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.westside.com/cdn/shop/articles/formal_wear_for_women.jpg?v=1662636789 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.pluchdesigns.com/cdn/shop/files/A317AC8B-E390-4CE2-8FE8-077DE5541E00.png?v=1756125219&width=500 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://parade.com/.image/w_3840,q_auto:good,c_limit/MTk5NjU5MjEyNDEyODIzMTY4/Amazon_semi-formal-attire-floral-blouse.jpg?arena_f_auto alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKWpCYY-Z-IvsoCGRZipU6I7kiovjQN6-e5vyONT-RLA&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHH1eTxm0cOgrRQnY7qiW6sFr7Q7MiKZQRTXTwLJZdTg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://i5.walmartimages.com/seo/Semi-Formal-Dress-for-Women-TIANEK-V-Neck-Floral-Shape-Ball-Graduation-Dress-Maxi-Long-Dress_55baafb2-f843-4948-97b1-81ade0d71152.274fbe3ccdae4028e9508196e78d3531.jpeg?odnHeight=768&odnWidth=768&odnBg=FFFFFF alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://images-na.ssl-images-amazon.com/images/I/61IK7QAidmL._UL500_.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSrGnFETH0_sFxSBo1Ofxh5YDRhaX520X1BVAGC_UlCVg&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBQDXPmyQOCwtUNmJjk4LYm5tlFjwBeiUNJFlQqvDjyw&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://gh.jumia.is/unsafe/fit-in/500x500/filters:fill(white)/product/12/066148/2.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://i5.walmartimages.com/seo/Women-s-Dress-Office-Dress-3-4-Sleeves-Pleated-Tie-Plus-Size-Dress-Leisure-Classic-Ladies-Chic-Dresses-Summer-Spring_524f8eef-ecfc-4b62-8522-43483ff8aae6.8d8d6b1d9177cd85f7bf8cf5bc81139e.jpeg?odnHeight=768&odnWidth=768&odnBg=FFFFFFhttps://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThZpM9_3cG9Dnm5UTnOuakSOJE1OYGKEzCbSRpTBDXkcsS3PUj1nwqT6o&s alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://cdn.shopify.com/s/files/1/0486/0634/7416/products/stylish_jacket_with_pockets_l1.jpg?v=1746683865 alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<div class="item formal female">
    <img src=https://www.houseoftailors.ae/assets/images/images/formal-women/women-formal-suits-1.jpg alt="Classic Formal">
    <span>Classic Formal</span>
</div>

<!-- TRADITIONAL -->
<div class="item traditional male">
    <img src=https://africablooms.com/wp-content/uploads/2019/03/Ghana-Wedding-Kente-Black-Suit-AFRICA-BLOOMS.jpg alt="Traditional Wear">
    <span>Traditional Wear</span>
</div>

<div class="item traditional male">
    <img src=https://www.mgkente.com/cdn/shop/files/4e85016ebb7a416adfb1dcc013a7b2f6-resized.jpg?v=1697319674&width=1946 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://vondeeworld.com/wp-content/uploads/2025/01/VondeeWorld-Northern-Ghana-Smock-for-Men-8a-430x602.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://vondeeworld.com/wp-content/uploads/2025/01/1acj-Vondeeworld-African-Smock-men.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://img.freepik.com/free-photo/side-view-man-wearing-native-attire_23-2150397430.jpg?semt=ais_hybrid&w=740&q=80 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://s.alicdn.com/@sc04/kf/H555dbb3b698c4cbb924520536400ed01a/Yibaoli-Factory-Supply-High-Quality-Fashion-Clothing-Ankara-Cotton-Traditional-African-Clothes-for-Men-African-Suit.jpg_300x300.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://ishafrica.com/wp-content/uploads/2022/12/Olu-Short-Sleeve-Mandarin-Button-Up-African-Print-Shirt-Black-Brown-Geometric.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://s.alicdn.com/@sc04/kf/Hb3d0ab10291642b9a05491c8757a9f20s/High-Quality-Polyester-Cotton-Mens-Fashion-Design-Africa-Traditional-Ethnic-Clothing-African-Dashiki-Shirts-African-Clothing.jpg_300x300.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://i.pinimg.com/736x/92/24/b5/9224b57605c07366e39211bdc284f0c7.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://i0.wp.com/clipkulture.com/wp-content/uploads/2021/05/13-45-48-173533678_294582045596910_5367122396622286927_n.jpg?fit=1080%2C1350&ssl=1 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://www.africablooms.com/wp-content/uploads/2019/02/Latest-African-Wear-for-Men-%E2%80%93-Dashiki-Shirt-for-Men-%E2%80%93-Ghana-Kente-Shirt-AFRICA-BLOOMS.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional male">
    <img src=https://danddclothing.com/cdn/shop/articles/Kente_Church_Dress_For_Men_7d510f77-3f6d-468a-9f08-372fffeb5dbc_1400x.jpg?v=1624374644 alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://i5.walmartimages.com/seo/BintaRealWax-Ankara-African-Dresses-Women-Traditional-Ghana-Elegant-Short-Sleeve-High-Waist-African-Print-Maxi-Dress-Africa-Clothing-Wedding-WY3629_d6139b31-afaa-45d5-9a39-86916cc74773.c0e28c1177e1a79e850ceef9dea48d51.jpeg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://karentinoboutique.com/cdn/shop/files/Africanprinteveningdress35A_2048x.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://i.etsystatic.com/17679582/r/il/561621/5100694146/il_fullxfull.5100694146_g2gg.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://img.kwcdn.com/product/fancy/53402367-aefd-44ef-bdfd-05575accfec9.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSG6SNctOBrKmk5CzVErJ2HjsrrNzoYU5RwdBlpAMltR_HyeUHc_oAXhic&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEcReBCUmxaZpjZAt5YmPPHbr9b6EtBt39F1DzEU_rKQ&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfjt8SOJPPrEug7Ya_G4n8wYzxFkULkX6BBDxELfdJDg&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://cdn.globalso.com/africlife/African-clothing-dashiki.jpg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLyARGz_7gIkbQjh95ARszJmcSIY6h17Zf0m9H_rHkyg&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female ">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKWQQilSFpK-hOkhV3mflz2riiUFVCBYDLPfSETqMCyw&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSR4LskOdrG5aUlRo3Wdc7SYM6AtCb50v4aIiPgwXHDnw&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXVl3XqVKT87SgVxtr-LyGltTJMZGaV-Wq5tU-p_pRNg&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://i5.walmartimages.com/seo/BintaRealWax-Ankara-African-Dresses-Women-Traditional-Ghana-Elegant-Short-Sleeve-High-Waist-Print-Maxi-Dress-Africa-Clothing-Wedding-WY3629_3de33c86-c7e9-40db-b93c-0e6ba6d0fdc6.d1899058b2148bcf42f1d97c9cc4db28.jpeg alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTukoja6gXpzVfjQzP-b-nJQ7-cF7Bi3zTkRLoqRNHJGA&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRHUG0QESI9Rf-RfcIux4GyAHs2zsWbhmNlCcHmzjKhZA&s alt="Cultural Dress">
    <span>Cultural Dress</span>
</div>

<div class="item traditional female">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQQf-2QRtqTqaWhwFsC-hqbppsKuG8QG5ApiZQSTtsVSg&s alt="African Style">
    <span>African Style</span>
</div>

<!-- STREET -->
<div class="item street male">
    <img src=https://image-cdn.hypb.st/https%3A%2F%2Fhypebeast.com%2Fimage%2F2024%2F06%2F17%2Fmilan-fashion-week-mens-ss25-street-style-026.jpg?q=75&w=800&cbr=1&fit=max alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://www.alanic.clothing/wp-content/uploads/2021/04/men-fashion-casual-streetwear-t-shirt.jpg alt="Urban Wear">
    <span>Urban Wear</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlz1j6Js1jy5QOfjJfeDjfJhxXhti8voXOz_FN_RibEA&s alt="Modern Street">
    <span>Modern Street</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzpsnOFXBxHB5GQG8UttEo4BRXdtOLZRrO18MCm7GE-Q&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://www.alanic.clothing/wp-content/uploads/2021/04/gray-casual-streetwear-t-Shirt.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://cdn.karmaloopassets.com/media//gene-cms/d/r/dropdown__400x400.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://streetwear.store/cdn/shop/files/streetwear-pants_300x.jpg alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://techwear-outfits.com/cdn/shop/files/streetwear-black-and-white-pants-techwear-334.webp?v=1692252521&width=720 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT54N3kpXRMHvW95okQ43bCEb-K2ee2FOmJj-KHbuN_WQ&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://scene7.zumiez.com/is/image/zumiez/397120-US alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://scene7.zumiez.ca/is/image/zumiez/189804-CA alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTymCvCYUyw2tTZAqp11WEcGpqQuqZoqs_cvZfB58uGlA&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRfGr5tI0aHcJogMYHcr1n0tTQNwP24OPT3FO-UKSowNQ&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTTKFClPkPh1GyNbVC-PbpaB4fC2CLIRZZpO8gkN9kCcA&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ62SO8QFbS0ULzfw6tP2a4jYIdiUC9eS4yqFDetZ10lw&shttps://cyber-techwear.com/cdn/shop/articles/product-image-1700778219.jpg?v=1719539357 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTI5vaFOsOBVvUDILrUVnybIqLbecSxDiDpLJ0W0G_5zw&s alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://thestreetsofseoul.com/cdn/shop/products/Cropped-Faux-Leather-Jacket-thestreetsofseoul-korean-street-style-minimal-streetwear-k-style-kstyle-mens-affordable-clothing-2.jpg?v=1655047850&width=1920 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://japanese-temple.com/cdn/shop/products/japanese-streetwear-pant-29605088821408_2000x.jpg?v=1628174705 alt="Street Fashion">
    <span>Street Fashion</span>
</div>

<div class="item street male">
    <img src=https://streetwear.com.ua/img/p/full/100/8045100a.jpg alt="Street Fashion">
    <span>Street Fashion
