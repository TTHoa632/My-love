<!DOCTYPE html> 
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Do - Đức Phúc</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: center;
            min-height: 100vh;
            background: url('https://cdn.xtmobile.vn/vnt_upload/news/01_2024/11/hinh-nen-dien-thoai-de-thuong-cho-nam-5-xtmobile.jpg') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px 20px;
            box-sizing: border-box;
            overflow: auto;
        }
        #content {
            width: 100%;
            max-width: 600px;
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin: 20px 0;
        }
        #video-container, #image-container, #message {
            margin-bottom: 30px;
            padding: 20px;
            border-radius: 10px;
            background: rgba(255, 255, 255, 0.9);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        iframe {
            width: 100%;
            height: auto;
            aspect-ratio: 16 / 9;
            border-radius: 10px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        #message {
            font-size: 16px;
            color: #000;
            font-weight: bold;
            text-align: justify;
            line-height: 1.6;
            padding-bottom: 50px;
            position: relative;
        }
        #love-message {
            position: absolute;
            bottom: 20px;
            right: 10px;
            font-size: 17px;
            color: black;
        }
        #greeting {
            font-size: 18px;
            font-weight: bold;
            text-align: center;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div id="content">
        <div id="video-container">
            <iframe id="youtube-video" src="https://www.youtube.com/embed/IOe0tNoUGv8?autoplay=1&enablejsapi=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        
        <div id="image-container">
            <img src="https://i.pinimg.com/736x/cc/32/33/cc3233026dc39b741c86e6f00093f988.jpg" alt="Hình ảnh mới">
        </div>
        
        <div id="message">
            <div id="greeting">Gửi S cute của iem</div>
            Anh này, hôm nay là 6/4 đó. Em chỉ muốn nói là, cảm ơn anh đã luôn ở bên cạnh em, cùng em trải qua những lúc vui buồn. Anh là chỗ dựa vững chắc cho em, là người em có thể tin tưởng và chia sẻ mọi điều. Chúc anh có một ngày 6/4 thật vui vẻ, luôn mạnh khỏe và thành công trong công việc. Nếu anh có mệt mỏi thì hãy quay đầu lại nha vì em sẽ luôn dõi theo và ủng hộ anh. (Những lời này chỉ có hiệu lực khi anh còn là người yêu của em, còn không MIỄN)
            <span id="love-message">Yêu anh ❤️</span>
        </div>
    </div>
    
    <script src="https://www.youtube.com/iframe_api"></script>
</body>
</html>
