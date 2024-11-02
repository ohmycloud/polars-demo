## How to run

```bash
RUST_LOG=info cargo run
curl "http://localhost:3333/delays"
curl "http://localhost:3333/delays?sorting=Asc&limit=5"
curl "http://localhost:3333/cities/52062/population"
curl "http://localhost:3333/cities/52062/area"
curl "http://localhost:3333/delays/80331/"
curl "http://localhost:3333/delays/corr/arrival_delay_m/departure_delay_m/"
curl "http://localhost:3333/delays/corr/arrival_delay_m/pop/"
```

See https://blog.logrocket.com/using-polars-rust-high-performance-data-analysis/
