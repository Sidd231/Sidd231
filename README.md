<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siddharth's Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0f172a;
            color: #f8fafc;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }
        .profile-card {
            background: #1e293b;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            text-align: center;
            max-width: 400px;
            width: 90%;
        }
        h1 { margin-bottom: 0.5rem; color: #38bdf8; }
        p { color: #94a3b8; margin-bottom: 1.5rem; }
        
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .btn {
            text-decoration: none;
            padding: 12px;
            border-radius: 8px;
            font-weight: bold;
            transition: transform 0.2s, background 0.2s;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .btn:hover { transform: translateY(-2px); }
        
        .gfg { background-color: #2f8d46; color: white; }
        .leetcode { background-color: #ffa116; color: #1a1a1a; }
        .sql-tag { 
            margin-top: 20px; 
            font-size: 0.8rem; 
            color: #64748b;
            border-top: 1px solid #334155;
            padding-top: 10px;
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <h1>Siddharth</h1>
        <p>B.Tech Student | AI & ML Enthusiast</p>
        
        <div class="links-container">
            <a href="https://www.geeksforgeeks.org/profile/siddhartha0p3zy" class="btn gfg" target="_blank">
                GeeksforGeeks Profile
            </a>
            
            <a href="https://leetcode.com/u/w0AoQjcb6W/" class="btn leetcode" target="_blank">
                LeetCode Profile
            </a>
        </div>

        <div class="sql-tag">
            💻 Database: SQL Enabled
        </div>
    </div>

</body>
</html>
