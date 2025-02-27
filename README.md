<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thông tin ngân hàng</title>
    <link rel="stylesheet" href="style.css">
</head>
<head>
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: white;
    text-align: center;
    margin: 0;
    padding: 20px;
}
.container {
    max-width: 400px;
    margin: auto;
    background: #1e1e1e;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.2);
}
.profile img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    margin-bottom: 10px;
}
.profile h2 {
    margin: 0;
    font-size: 20px;
}
.bank-info h3 {
    margin-top: 20px;
}
.bank-card {
    background: #292929;
    padding: 15px;
    border-radius: 8px;
    margin: 10px 0;
}
    .bank-card img {
    width: 60px;
    margin-bottom: 10px;
}
    button {
    background-color: #ff9800;
    border: none;
    color: white;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}
button:hover {
    background-color: #e68900;
}
.facebook-btn {
    display: inline-block;
    margin-top: 15px;
    background: #1877F2;
    color: white;
    padding: 10px;
    text-decoration: none;
    border-radius: 5px;
}
.facebook-btn:hover {
    background: #165dbb;
}
</style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="https://i.imgur.com/MwcMXg8.jpeg"alt="Avatar">
            <h2>Chấn Khang</h2>
            <p>💰 Đổi Tiền • GDTG • Sell/Thu Acc ADV,prem dra bf</p>
        <div class="bank-info">
            <h3>Thông tin ngân hàng</h3>
            <div class="bank-card">
               <img src="https://cdn.haitrieu.com/wp-content/uploads/2023/07/co-ngan-hang-vietcombank-350x233.png" alt="VietComBank">
                <p><strong>VietComBank</strong></p>
                <p>STK: <span class="account-number">1040655383</span></p>
                <p>CTK:DOAN CHAN KHANG </p>
                <button onclick="copyToClipboard('1040655383')">Copy</button>
            </div>
            <div class="bank-card">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARsAAACyCAMAAABFl5uBAAAA8FBMVEX///8BUIn+/v7/MTEAP38ATIa5yNj/LS3/8/MAS4b/Kyvz+Pr/Hx//+vr/ODj/OzsARoP/T0//Fhb/JycAVI0TWY8nW4//39//6+v/HBybtcv/IiL/fn4AOXwAO31QdZ4nYZP/ZmYoapr/tbVfkbQ4daIAQoH/qqrm7vM6Z5Zznr1Uia9BfKZHgKk8eKMhZZf/Vlb/jIz/CwuJrcd3ob//19f/RET/yMjG1uNllLZsiKuHm7je6O8AMnisvtH/hIT/mZn/cHD/n5//u7v/X1+Wts2XqcHCzNqqt8the6FIaJV4ja6CnbqPoLu0v9AAK3XTp20XAAAKFUlEQVR4nO2deUO6SBiAQUQE1FA8M+z26DQts7K77XR/+/2/zb4zAzKDgNZupTDP/pEK+JNn32NeUhMEDofD4XA4HA6Hw+FwOBwOh8PhcDicCKAPh8P2b7+IxWT0F9C/Sfz261hAhshMv3/6F5fjZdhHZsDNaZ/LYRn2bTOne3unXA7N0BYDZvYudrgciuGpHTJg5uJiZ3+Py3EYnjohA2J2dvb3Dy/0335NC8JwD5u5wGb2EYcH+1wOAtTsOWaQmkPgYHefp5UgpC7YkAExB0dHu1uHPHJADRMyB2BmF9g63o27nNTORAxJpiNkZgs43oi5HFCzQyXTkWvm+HijtBVnOal9N2QODmgxYKZUEjvxlXOzT5vZpUIGmSkVRbUcVzk3h2zI7DJiiiJgxFQOVjOVTK4ZOb5yVg+oxuQTMjZxTKvVo1kh48gpxk0OUsO07A1kpliiQyamkbO6S4XMlhMy6ro6rQbJidMV9tVdzyqPtOyyoMq+csT4RA6o8asy1lC4Sfq5iVFa9bemQgbVX+NSSAjvvlklqqV4pFX/mDUDYnAmWXoiIQwtXzcgJw6R0z/2b9nNZyEBci6NADnF6EcOVmO3bHqVJ5chbMCN3vB3AwU56nL6G5Mpm13/NlIobEDOs385jn5ajUvUlM2c+BtRA5R9+3jkIwfU+IxMCGvkuBFeAspxtOWMS1TLZs7a+JiETWAfF6PcysfipP560kZu6gnXzSgwcERVjqacseyXTJjkqxs2KHCCKk5U5YzVADGofzNqho3ApIpmzRkbQWbwIEW76TQvm8FyZDVqcj4Clrs4FN4YNX+sd6ETnFWRi5ywQBCTbcqNoKvXI0irkP2jJecyaK2LaP7NhM2VBf1ceAspOaIaobQKVSPKCVpN28LzeDu4j4tR6lbhahp/mLB5s3A/F57DslCUjdFvn9X/Qrga9Z0JmxerbN8KSyo4zIhC5ISWYXqQIoOm9WLP43/CyjFq5csfOeFRwwxSKJOsST8PGavsyFl2OTOiBl8IddGb1qSfh41VJHLk5ZYzS03ymQmbD+uKmsfD1os4cpY6rcbhCQWDFFOIR9ciPY/rM44GOct7JbA9I2rExgs7fxvsMjDw8qhDcvW3T/HLpMJbzdQg1ZCbnq4VMlbZT7CsBPyW0g0b1oQsiwZrK+i3VRFwM6PTNK8YEX+jDPRcrggdq2AFMP7tU/w6/u+LmKDT8/coiRJI7jBu2tehT9BY4kbVNkIKhneQIh49l0evwvq4tbylGBgZgZHjiZBJaTF0pgiF2F1uNWGRc81WlklL8kwRwWPVsquByBED3jVyyez26ra06/Zcv3RYfjUgp+grpznSKdrUG7Y8q56h/0LAev3tE/s/GMk+cmSxmaRRZReLXS37vuukEYGoQfjJkcvBGCJdjH0nj6iogYIse2tGIxWy+5v1PGOssm5+7LV/O22VjRx1nenTLELbSraZR7xjVZTUgBy2WyVHIW5gerAumcBJWRFWA3JKlBzjKkxNIqGXw8aqqKlh5XiWvtOBk7LYRfOIGqsakVNDy2FHJl8579afgLEqimrcmsO+o8TfzcgymPu608ejl1AEu5Wzg1SAnI8ke3HHnimuI6pGEHQ0PrAjQZAbPcn+Uo/MolbYsmjJQTWn0Z7DDQSKtT51DeM6wmpATjn5POeuZcg9mksjdDEdAdrlm9R8PDfLzP2baEcNoi1bybkwRJm5/0/k1aDICb/AHkDUE4qgl74gJ/oJRdDLM94EME2UmzeLvvFJOdbLb7/kn6P9KTlyPGqNw6ciJxkrNZ+Sk4xRQhHmLshxqjUOc8qxhrOfKnronTnkXMdSzVxyGjFVM1uOnIytmllyYq1mhpx4qwmVE88ORRMoh6sBOe9+cuT4digaXzlxrzUO03LkJldj45XD1VAkmIIc83WNF1qOvMzvNv8OEuuOHNniajw4cnhC+ZB4s9CHhJb+E6rfw2tHLH1E4WPf34K+vJ+/5HA4HA6Hw+FwOJwvobMkyCPUxqk9yb1E9ez8rJq1t6XT6exkx2wakyW3qAcTZE9nK03W99HfRVdLNOJI0OHHOtmY2CqVNsgfPRxedsrkC4zxh8OzrXymBgxO8LlnByu5Ljmv87XuYAUhnQjCfW7FtE/3VlqRKqBmxWbQXTt3XoR7zN2Pnfgc6A2ZpgluRFl13GzIchHfumw4n3Q2kJt0t6AomqkpSiYHJyxkc4qWRxIT9wVTIdTBzaapFGw3a6aSQW6UCWbhHm/Lbk6Oydz9uIAQPF/+ZICbojjl5rkhyga5uIe/VGCzLmnm5v2TaUpapordKNjNSUGSMhnXjSYV7D+2uWZKdeRGUtB/oKEuSbVbvKUGx9QX0A2pIqmmaKza9cbHjV6UxeZqe1JvznqSMgAlQvW+0GtlXTfZniTVW25F8XWj5VFxqT4gJZCRVfhZ3/avQotAKgnnbt/2cTNMigb9HRStjJTZJjdPcNFw3JwXJPOE2jHAzeSR2vn0MYvGDDcv1GbEQx2flYvj5rEm1bapx0PdtOBZHuFHDf9YWGa4QZvpTxSCAvOePt5xs51hzzPUzZ0pFc5xEC6XG7u0UG5e3QUQLhHmoFWZVAfazTa1VPF308UPnEGXM9MkQR8XcXlj43GDmhJGFh03okoeId/PcgftSMnUcvetKj6GciOZdUwP5ZZ/n8rdA92MovVaAnbDHLNoTLmxEV039mNJ8t01d4WMBnq0GmnDtBt7qVIIdiNpADTyLq5ZLfeYhcwtjxtZ3MDf2LLhupGLZOEs23Wn+tA1e3U4z9qTwLhRcmTdq6Hz9Hej9Xq9giYpLbwB3Cj2WllZAjdOLRamazH1Z9PTZw8D+H/ee/TWYvvjvUKAGyVfrVTOn+pSAcccqsXn1DGLxif7lAt0c3Pta30qD9vOhCXsU+QmtfZj1jdC9cy+kYWhYZNZ32S865vJPOVx8whrPhQ428u9vgE3zNd/nuXQSI2oZCTtnl0Xr1E7gpCCrTEPdSZNu8nWoTZlyTG333hu/5UZbvSSLBrjUZsgVHqaJp2jXKk8aVLtgZqnoLfX7ypVTBrHhjbAg/oJJB+q2tTaDwUVdKo01Kz6g3vMojHDjbBqwYjexCQhgG4LklKTut1cTYN5PE3N4Q9ITi2DKKB4ykPO1QZPXROm7h6KIHpmyEhoViezOzmmt4ABlGrIk+9a1mGZN3GjquT6zfjaUFV8CcdAyXXSs6+4aDUTnXEWFGE3wm2vbmqYOkqu6qCg2ZdzyMIurcCe5NmrPcUcoBtrvTo5RMss4ND5Uu6UnUakdzode+hOrMNt0mdGz4cdwge6e7a2Uq/V6rmnFrk81c3nN8mOlbtNuIMg59nqKrVCwRyckBV0GjZs2v/SZj6PE4465u7bT/UnyMIipTrX/JOuwJ7f/XI4HA6Hw+FwOBwOh8PhcDgcDofD4XA4HM4i8i9HglGcrQG6ugAAAABJRU5ErkJggg==" alt="THE SIEU RE">
                <p><strong>THE SIEU RE</strong></p>
                <p>STK: <span class="account-number">0325279027</span></p>
                <p>CTK:Chan Khang </p>
                <button onclick="copyToClipboard('0325279027')">Copy</button>
            </div>
            <div class="bank-card">
                <img src="data:image/png;base64,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" alt="MoMo">
                <p><strong>MoMo</strong></p>
                <p>STK: <span class="account-number">0325279027</span></p>
                <p>CTK: CHAN KHANG </p>
                <button onclick="copyToClipboard('0325279027')">Copy</button>
            </div>
        <a href="https://www.facebook.com/profile.php?id=100088077474675" class="facebook-btn">FACEBOOK CHÍNH CỦA TUI</a>
    </div>
  <script>
        function copyToClipboard(text) {
            navigator.clipboard.writeText(text).then(() => {
                alert("Đã sao chép số tài khoản: " + text);
            });
        }
    </script>
