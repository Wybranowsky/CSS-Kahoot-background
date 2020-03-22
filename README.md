# CSS-Kahoot-background
CSS3 rainbow Kahoot background

```html
    @keyframes bgcolor {
        0% {
            background-color: #45a3e5
        }

        30% {
            background-color: #66bf39
        }

        60% {
            background-color: #eb670f
        }

        90% {
            background-color: #f35
        }

        100% {
           background-color: #864cbf
        }
    }

    body {
        -webkit-animation: bgcolor 20s infinite;
        animation: bgcolor 10s infinite;
        -webkit-animation-direction: alternate;
        animation-direction: alternate;
    }
```
