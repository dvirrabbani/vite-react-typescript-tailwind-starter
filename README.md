## Install tailwindcss v4 
npm install tailwindcss @tailwindcss/postcss postcss


### postcss.config.js
```export default {
  plugins: {
    "@tailwindcss/postcss": {},
  }
}
```

### index.css 
@import "tailwindcss";