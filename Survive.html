// Game variables
let canvas, ctx;
let player;
let enemies = [];
const enemySpeed = 2;
const playerSpeed = 5;
const spawnRate = 1500; // Enemy spawns every 1500ms

// Player object
function Player(x, y) {
    this.x = x;
    this.y = y;
    this.width = 20;
    this.height = 20;

    this.draw = function() {
        ctx.fillStyle = 'blue';
        ctx.fillRect(this.x, this.y, this.width, this.height);
    };

    this.move = function(direction) {
        switch (direction) {
            case 'up':
                this.y -= playerSpeed;
                break;
            case 'down':
                this.y += playerSpeed;
                break;
            case 'left':
                this.x -= playerSpeed;
                break;
            case 'right':
                this.x += playerSpeed;
                break;
        }
    };
}

// Enemy object
function Enemy(x, y) {
    this.x = x;
    this.y = y;
    this.width = 20;
    this.height = 20;

    this.draw = function() {
        ctx.fillStyle = 'red';
        ctx.fillRect(this.x, this.y, this.width, this.height);
    };

    this.update = function() {
        // Simple logic to follow the player
        if (this.x < player.x) {
            this.x += enemySpeed;
        } else {
            this.x -= enemySpeed;
        }

        if (this.y < player.y) {
            this.y += enemySpeed;
        } else {
            this.y -= enemySpeed;
        }
    };
}

// Initialize the game
function init() {
    canvas = document.getElementById('gameCanvas');
    ctx = canvas.getContext('2d');
    player = new Player(canvas.width / 2, canvas.height / 2);
    setInterval(spawnEnemy, spawnRate);
    window.requestAnimationFrame(gameLoop);
}

// Game loop
function gameLoop() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    player.draw();
    enemies.forEach(enemy => {
        enemy.update();
        enemy.draw();
    });
    window.requestAnimationFrame(gameLoop);
}

// Spawn an enemy
function spawnEnemy() {
    const x = Math.random() * canvas.width;
    const y = Math.random() * canvas.height;
    enemies.push(new Enemy(x, y));
}

// Listen for key presses
window.addEventListener('keydown', function(e) {
    switch (e.key) {
        case 'ArrowUp':
            player.move('up');
            break;
        case 'ArrowDown':
            player.move('down');
            break;
        case 'ArrowLeft':
            player.move('left');
            break;
        case 'ArrowRight':
            player.move('right');
            break;
    }
});

// Start the game
window.onload = init;
