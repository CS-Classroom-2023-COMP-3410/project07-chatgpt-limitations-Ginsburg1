First assignment:

i prompeted CoPiolet with this:
```
implement it so there are 2 people playing. as well, make it so that it keeps score. Highlight hte tiles in blue if player 1 gets it correct and green if player 2

```


Second assignment:

I fixed a couple of things but mainly this

```
/* 🎮 Centered Game Container */
.game-container {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: calc(100vw - 240px); /* 120px padding on each side */
  height: min(calc(100vh - 240px), 600px); /* 120px padding on top and bottom, max 600px */
  max-width: 600px; /* Maximum width */
  background: #fff;
  border: 5px solid #333;
  border-radius: 10px;
  padding: 20px;
  z-index: 1000;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  display: flex;
  flex-direction: column;
  align-items: center;
}```

