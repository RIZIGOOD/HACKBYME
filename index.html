from flask import Flask, request
import webbrowser
import threading
import time
import atexit
import logging

app = Flask(__name__)

# Налаштування логування для запису в файл
logging.basicConfig(filename='access_logs.txt', level=logging.INFO, format='%(asctime)s - %(message)s')

@app.route('/')
def index():
    # Отримуємо інформацію про запит
    ip_address = request.remote_addr  # IP адреса користувача
    user_agent = request.headers.get('User-Agent')  # Інформація про браузер
    browser_info = "Unknown Browser"

    if "Chrome" in user_agent:
        browser_info = "Chrome"
    elif "Firefox" in user_agent:
        browser_info = "Firefox"
    elif "Safari" in user_agent:
        browser_info = "Safari"
    
    # Логування в файл
    log_message = f"IP Address: {ip_address}, Browser: {browser_info}, User-Agent: {user_agent}"
    logging.info(log_message)
    
    # Виводимо інформацію в консоль
    print(f"Visit Information:\n\nIP Address: {ip_address}\nBrowser: {browser_info}\nUser-Agent: {user_agent}")

    return """
    <html>
    <head>
        <style>
            body {
                background-color: #000;
                color: #00ff00;
                font-family: 'Courier New', Courier, monospace;
                margin: 0;
                overflow: hidden;
            }
            #terminal {
                position: absolute;
                top: 0;
                left: 0;
                right: 0;
                bottom: 0;
                padding: 20px;
                white-space: pre-wrap;
            }
            #warning {
                position: absolute;
                top: 0;
                left: 0;
                right: 0;
                bottom: 0;
                background-color: rgba(255, 0, 0, 0.5);
                display: none;
            }
        </style>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    </head>
    <body>
        <div id="terminal">Initializing hack sequence...</div>
        <div id="warning">
            <h1>WARNING!</h1>
            <p>SYSTEM COMPROMISED!</p>
            <p>DATA ENCRYPTION IN PROGRESS...</p>
        </div>
        <script>
            const messages = [
                'Connecting to secure server...',
                'Bypassing firewall...',
                'Access granted. Retrieving data...',
                'Decrypting files...',
                'Hack complete. Downloading contents...',
                'Downloading file 1 of 10...',
                'Downloading file 2 of 10...',
                'Downloading file 3 of 10...',
                'Downloading file 4 of 10...',
                'Downloading file 5 of 10...',
                'Downloading file 6 of 10...',
                'Downloading file 7 of 10...',
                'Downloading file 8 of 10...',
                'Downloading file 9 of 10...',
                'Downloading file 10 of 10...',
                'Process finished.',
            ];
            const warningMessages = [
                'SYSTEM COMPROMISED!',
                'DATA ENCRYPTION IN PROGRESS...',
                'FILE SYSTEM CORRUPTED!',
                'HACKER HAS TAKEN CONTROL OF YOUR SYSTEM!',
                'YOU HAVE 5 MINUTES TO PAY THE RANSOM!',
            ];

            let i = 0;
            function typeMessage() {
                if (i < messages.length) {
                    terminal.innerHTML += messages[i] + '<br>';
                    i++;
                    setTimeout(typeMessage, 50);
                } else {
                    setTimeout(closeWindow, 2000); // Close browser after delay
                }
            }

            let j = 0;
            function typeWarningMessage() {
                if (j < warningMessages.length) {
                    warning.innerHTML = warningMessages[j];
                    j++;
                    setTimeout(typeWarningMessage, 3000);
                } else {
                    warning.style.display = 'none';
                }
            }

            function closeWindow() {
                window.close();
            }

            typeMessage();
            warning.style.display = 'block';
            typeWarningMessage();

            const scene = new THREE.Scene();
            const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
            const renderer = new THREE.WebGLRenderer();
            renderer.setSize(window.innerWidth, window.innerHeight);
            document.body.appendChild(renderer.domElement);
            const geometry = new THREE.BoxGeometry();
            const material = new THREE.MeshBasicMaterial({color: 0x00ff00});
            const cube = new THREE.Mesh(geometry, material);
            scene.add(cube);
            camera.position.z = 5;
            function animate() {
                requestAnimationFrame(animate);
                cube.rotation.x += 0.01;
                cube.rotation.y += 0.01;
                renderer.render(scene, camera);
            }
            animate();
        </script>
    </body>
    </html>
    """

def open_browser():
    webbrowser.open('http://127.0.0.1:5000/')

if __name__ == '__main__':
    threading.Timer(1, open_browser).start()
    app.run(debug=True)
    atexit.register(lambda: time.sleep(5))  # Wait for threads to complete before closing
