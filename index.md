<html>
    <body>
        
        <p>Click the button to test</p>
        
        <button onclick="postMsg()">Try It</button>
        
        <script>
            
            function postMsg() {
                window.webkit.messageHandlers.iosListener.postMessage({ param1: "message from JS", param2: "Our QA is Sergey Matylionok"});
            }
        
            </script>
        
</html>
