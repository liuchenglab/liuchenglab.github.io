---
layout: single
title: "Members"
permalink: /members/
---

<html>
<head>
    <style>
        .section-header {
            width: 100%;
            padding: 1rem;
            margin: 2rem 0 1rem 0;
            background-color: #f0f0f0;
            border-left: 4px solid #1e88e5;
            font-size: 1.5rem;
            font-weight: bold;
        }

        .members-grid {
            display: grid;
            grid-template-columns: minmax(800px, 1fr);
            gap: 2rem;
            padding: 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .member-card {
            display: grid;
            grid-template-columns: 200px 1fr;
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.2s;
            background-color: #ffffff;
            align-items: center;
        }

        .member-card:hover {
            transform: translateY(-5px);
        }

        .member-photo {
            padding: 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100%;
        }

        .member-photo img {
            width: 100%;
            height: auto;
            max-height: 240px;
            object-fit: contain;
            border-radius: 4px;
        }

        .member-info {
            padding: 1.5rem;
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .member-info h2 {
            font-size: 1.2rem;
            margin: 0;
            color: #333;
        }

        .member-info p {
            margin: 0;
            color: #666;
        }

        .member-info a {
            color: #1e88e5;
            text-decoration: none;
        }

        .member-info a:hover {
            text-decoration: underline;
        }

        @media (max-width: 800px) {
            .members-grid {
                grid-template-columns: 1fr;
                padding: 0.5rem;
            }
            
            .member-card {
                grid-template-columns: 1fr;
            }
            
            .member-photo {
                max-width: 200px;
                margin: 0 auto;
            }
        }
    </style>
</head>
<body>
    <div class="section-header">Assistant Professor</div>
    <div class="members-grid">
        <div class="member-card">
            <div class="member-photo">
                <img src="../images/LIU.png" alt="LIU Cheng">
            </div>
            <div class="member-info">
                <h2>Prof. LIU Cheng (Assistant Professor, 2022.10-present)</h2>
                <p><strong>Ph.D:</strong> Stanford University </p>
                <p><strong>Msc:</strong> Stanford University </p>
                <p><strong>B.E:</strong> Nanjing University of Aeronautics and Astronautics</p>
                <p><strong>Email:</strong> cliu647@cityu.edu.hk</p>
                <p><strong>Personal website:</strong> <a href="https://www.cityu.edu.hk/stfprofile/ChengLiu.htm" target="_blank">https://www.cityu.edu.hk/stfprofile/ChengLiu.htm/</a></p>
            </div>
        </div>
    </div>

    <div class="section-header">Postdoctoral Fellows</div>
    <div class="members-grid">
        <div class="member-card">
            <div class="member-photo">
                <img src="../images/LSF.png" alt="LI Shufei">
            </div>
            <div class="member-info">
                <h2>Dr. LI Shufei (Postdoctoral Fellow, 2025.01-present)</h2>
                <p><strong>Ph.D:</strong> The Hong Kong Polytechnic University </p>
                <p><strong>Email:</strong> shufei.li@outlook.com </p>
            </div>
        </div>

        <div class="member-card">
            <div class="member-photo">
                <img src="../images/shiyan.jpg" alt="SHI Yan">
            </div>
            <div class="member-info">
                <h2>Dr. SHI Yan (Postdoctoral Fellow, 2025.02-present)</h2>
                <p><strong>B.E:</strong> Northwestern Polytechnical University </p>
                <p><strong>Ph.D:</strong> Northwestern Polytechnical University </p>
                <p><strong>Email:</strong> yshi58@cityu.edu.hk </p>
            </div>
        </div>
    </div>

    <div class="section-header">PhD Students</div>
    <div class="members-grid">
        <div class="member-card">
            <div class="member-photo">
                <img src="../images/yc1.png" alt="ZHANG Yingchao">
            </div>
            <div class="member-info">
                <h2>ZHANG Yingchao (PhD student, 2023.09-present)</h2>
                <p><strong>B.E:</strong> Shandong University</p>
                <p><strong>M.E:</strong> Shandong University</p>
                <p><strong>Email:</strong> yingchao.zhang@my.cityu.edu.hk</p>
                <p><strong>Tel:</strong> +852-56396211</p>
                <p><strong>Personal website:</strong> <a href="https://yingchaoao.github.io/" target="_blank">https://yingchaoao.github.io/</a></p>
            </div>
        </div>
        <div class="member-card">
            <div class="member-photo">
                <img src="../images/xuebing.png" alt="XU Xuebing">
            </div>
            <div class="member-info">
                <h2>XU Xuebing (PhD student, 2024.01-present)</h2>
                <p><strong>B.E:</strong> Huazhong University of Science and Technology</p>
                <p><strong>M.E:</strong> Huazhong University of Science and Technology</p>
                <p><strong>Email:</strong> xuebinxu-c@my.cityu.edu.hk </p>
            </div>
        </div>
        <div class="member-card">
            <div class="member-photo">
                <img src="../images/cy.png" alt="CHEN Yan">
            </div>
            <div class="member-info">
                <h2>CHEN Yan (PhD student, 2024.09-present)</h2>
                <p><strong>B.E:</strong> National University of Defense Technology</p>
                <p><strong>Msc:</strong> City University of Hong Kong</p>
                <p><strong>Email:</strong> ychen935-c@my.cityu.edu.hk</p>
                <p><strong>Tel:</strong> +852-69112315</p>
            </div>
        </div>
    </div>
</body>
</html>

