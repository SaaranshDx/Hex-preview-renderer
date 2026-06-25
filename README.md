# Hex preview renderer 
built on cloudflare workers and browser run
to render cape previews

how to use:
```bash
curl -X POST <url> ^
  -F "cape=@cape.png" ^
  --output out.png
```

The server will return the rendered image in the response that is a **png file** of the rendered cape.


