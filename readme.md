### 📦 Dependencies

- astro 4.0+
- node v20.10+
- npm v10.2+
- tailwind v3.3+

### 👉 Install Dependencies

```bash
npm install
```

### 👉 Development Command

```bash
npm run dev
```

### 👉 Build Command

```bash
npm run build
```

### 👉 Build and Run With Docker

```bash
docker build -t astroplate .
# or
# docker --build-arg INSTALLER=npm build -t astroplate .
# or
# docker --build-arg INSTALLER=pnpm build -t astroplate .

docker run -p 3000:80 astroplate
# or
# docker run --rm -p 3000:80 astroplate
```

To access the shell within the container:

```bash
docker run -it --rm astroplate ash
```
