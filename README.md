# Usage
Edit the license file

```
npm install
npm run dev
```
## Docker
If using /public uncomment from Dockerfile

`# COPY --from=builder /app/public ./public`

then

`docker-compose up --build --pull always`

# License
All code in this repository is dual-licensed under either [License-MIT](./LICENSE-MIT) or [LICENSE-APACHE](./LICENSE-Apache) at your option. This means you can select the license you prefer. [Why dual license](https://github.com/bevyengine/bevy/issues/2373)
