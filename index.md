<html>
    <body>
        
        <p>Listener sample</p>
        
        <script>
            window.webkit.messageHandlers.iosListener.postMessage({ param1: "message from JS", param2: "1000"});
            </script>        
    </body>
</html>
