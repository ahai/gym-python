<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sequence Diagram - Authentication Flow</title>
    <script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            background: white;
            border-radius: 12px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            padding: 40px;
            max-width: 900px;
            width: 100%;
        }
        
        h1 {
            color: #333;
            margin-bottom: 10px;
            font-size: 28px;
        }
        
        .subtitle {
            color: #666;
            margin-bottom: 30px;
            font-size: 14px;
        }
        
        .diagram-wrapper {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 20px;
            overflow-x: auto;
        }
        
        .mermaid {
            display: flex;
            justify-content: center;
        }
        
        .info-box {
            background: #e7f3ff;
            border-left: 4px solid #2196F3;
            padding: 15px;
            margin-top: 20px;
            border-radius: 4px;
            font-size: 13px;
            color: #555;
        }
        
        .info-box strong {
            color: #1976D2;
        }
        
        footer {
            text-align: center;
            margin-top: 30px;
            color: #999;
            font-size: 12px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Authentication Flow Sequence Diagram</h1>
        <p class="subtitle">User login process with token-based authentication</p>
        
        <div class="diagram-wrapper">
            <div class="mermaid">
                sequenceDiagram
                    actor User
                    participant Client
                    participant Server
                    participant Database

                    User->>Client: Enter credentials
                    Client->>Server: POST /login
                    activate Server
                    Server->>Database: Query user by email
                    activate Database
                    Database-->>Server: User record
                    deactivate Database
                    Server->>Server: Verify password
                    alt Authentication Success
                        Server->>Database: Update last_login
                        Database-->>Server: Confirmed
                        Server-->>Client: JWT token
                        Client-->>User: Login successful
                    else Authentication Failed
                        Server-->>Client: Error 401
                        Client-->>User: Invalid credentials
                    end
                    deactivate Server
            </div>
        </div>
        
        <div class="info-box">
            <strong>Diagram Description:</strong> This sequence diagram illustrates the authentication workflow in an AI-MCP DSWithBappy system. It shows the interaction between User, Client, Server, and Database components during a login request, including success and failure scenarios.
        </div>
        
        <footer>
            <p>Generated with Mermaid.js - Powered by Mermaid Diagram Library</p>
            <p>Interactive and responsive sequence diagram for GitHub documentation</p>
        </footer>
    </div>
    
    <script>
        mermaid.initialize({ startOnLoad: true, theme: 'default' });
        mermaid.contentLoaded();
    </script>
</body>
</html>
