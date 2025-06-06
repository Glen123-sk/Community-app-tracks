body {
  background: radial-gradient(circle at center, #1e1e2f, #0d0d1a);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.center {
  text-align: center;
}

.play-button {
  font-size: 60px;
  border: none;
  border-radius: 50%;
  width: 120px;
  height: 120px;
  color: white;
  background: linear-gradient(135deg, #ff416c, #ff4b2b);
  box-shadow: 0 0 20px rgba(255, 65, 108, 0.6);
  cursor: pointer;
  transition: all 0.3s ease;
  animation: pulse 2s infinite;
}

.play-button:hover {
  transform: scale(1.1);
  box-shadow: 0 0 30px rgba(255, 255, 255, 0.8);
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}
