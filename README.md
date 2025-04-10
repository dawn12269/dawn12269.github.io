<html lang="zh-CN">
 <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us</title>
    <!-- 引入Font Awesome图标库 -->
    <link
     rel="stylesheet"
     href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
    />
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
        }
        /* 新增标题样式 */
        .page-title {
            font-size: 32px;
            font-weight: bold;
            color: #003366;
            margin-bottom: 10px;
            text-align: left;
        }
        /* 新增分隔线样式 */
        .title-divider {
            height: 2px;
            background-color: #003366;
            margin-bottom: 20px;
            width: 100%;
        }
        .header {
            margin-bottom: 20px; /* 与下方内容的间距 */
            text-align: left; /* 文字靠左对齐 */
        }
        .header .line1 {
            font-size: 28px;
            font-weight: bold; /* 第一行加粗 */
            margin-bottom: 5px; /* 两行文字之间的间距 */
        
        }
        .header .line2 {
            font-size: 18px;
            color: #666; /* 第二行文字颜色稍浅 */
        }
        .container {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .image {
            width: 150px; /* 正方形图片宽度 */
            height: 150px; /* 正方形图片高度 */
            object-fit: cover; /* 保持图片比例 */
            margin-right: -30px; /* 图片与文字背景重叠的部分 */
            z-index: 1; /* 图片在文字背景上方 */
            position: relative; /* 确保z-index生效 */
        }
        .text-box {
            background-color: #003366; /* 深蓝色背景 */
            color: white; /* 文字颜色 */
            padding: 15px; /* 调整内边距 */
            width: 760px; /* 文字背景宽度 */
            height: 120px; 
            display: flex;
            justify-content: center; /* 水平居中 */
            align-items: center; /* 垂直居中 */
            font-size: 14px;
            line-height: 1.5;
            border-radius: 0px; /* 圆角 */
            white-space: normal; /* 允许文字换行 */
            word-break: break-word; /* 确保长文字换行 */
            margin-left: 20px; /* 文字背景向左移动，与图片重叠 */
            z-index: 0; /* 文字在图片上方 */
            position: relative; /* 确保z-index生效 */
            text-align: center; /* 文字内容居中 */
        }
        
        .text-box strong {
            font-weight: bold; /* 加粗文字 */
        }
    </style>
</head>
<body>
    <!-- 新增标题和分隔线 -->
    <h1 class="page-title">OASIS GROUP</h1>
    <div class="title-divider"></div>

    <!-- 最上方两行文字 -->
    <div class="header">
        <div class="line1" >"Dedication Enables Stability"</div>
        <div class="line2">
            In a competitive market, Oasis Group stands out through expertise, reliable routes, and a customer-first ethos.
            </div>
    </div>

    <!-- 第一部分：专注西非航线 -->
    <div class="container">
        <img src="https://i.ibb.co/tMjyBhwy/c.jpg" alt="c" class="image"/></a>
        <div class="text-box">
            <div>
                <strong>West Africa Specialists</strong><br>
                <span>Decades of experience, robust port networks, and routes from China to key West African ports.</span>
            </div>
        </div>
    </div>

    <!-- 第二部分：精通件杂货运输 -->
    <div class="container">
        <img src="https://i.ibb.co/VYxz4CJ2/c.jpg" alt="精通件杂货运输" class="image">
        <div class="text-box">
            <div>
                <strong>Breakbulk Expertise</strong><br>
                <span>Safe and efficient handling of project cargo, machinery, vehicles, and steel.</span>
            </div>
        </div>
    </div>

    <!-- 第三部分：卓越的服务品质 -->
    <div class="container">
        <img src="https://i.ibb.co/JRKh8JzM/c.jpg" alt="卓越的服务品质" class="image">
        <div class="text-box">
            <div>
                <strong>Service Excellence</strong><br>
                <span>Customer-centric teams and streamlined operations for seamless experiences.</span>
            </div>
        </div>
    </div>
    <div class="title-divider"></div>
    
    <div class="content">
        
        
        <div class="contact-info">
            <!-- Phone group -->
            <div class="phone-group">
                <div class="label">Telephone : 021 60950642</div>
                <div class="phone-item">
                    <span class="phone-type">Mobile-Summer : 0086 15921433450</span>
                    <span></span>
                </div>
                <div class="phone-item">
                    <span class="phone-type">Mobile-Jenny :</span>
                    <span>0086 13585677878</span>
                </div>
                <div class="phone-item">
                    <span class="phone-type">Mobile-Jacky :</span>
                    <span>0086 18916194572</span>
                </div><br>
               
            
            <!-- Other contact information -->
            <div class="contact-item">
                <span class="label">Email :</span>
                <span>op@oasis-group.com.cn</span>
            </div><br>
            
            <div class="contact-item">
                <span class="label">Website:</span>
                <span>http://oasis-group.com.cn</span>
            </div><br>
            
            <div class="contact-item">
                <span class="label">Address :</span>
                <span>Room 1407, Building D, Pudong Square, No.1759 Zhongshan
                    North Road, Shanghai</span>
            </div><br>
            
            <div class="contact-item">
                <span class="label">Postal Code :</span>
                <span>200061</span><br>
            </div>
        </div>
    </div>

</body>
</html>
