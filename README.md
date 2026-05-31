# Supply Chain Tower Agent Website

This is a free static website that embeds the deployed Hugging Face chatbot:

`https://huggingface.co/spaces/pimparkaramit/SupplyChainTower-Agent`

## Files

- `index.html` - website page with live chatbot iframe
- `styles.css` - visual styling
- `assets/supplychaintowe-agent_v1.0.mp4` - demo video

## Run Locally

From this folder:

```powershell
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```

## Free Hosting Options

### Option 1: GitHub Pages

1. Create a new GitHub repository.
2. Upload the files from this folder.
3. Go to repository `Settings > Pages`.
4. Select deploy from branch.
5. Choose `main` and `/root`.
6. GitHub will give you a public website URL.

### Option 2: Cloudflare Pages

1. Create a Cloudflare Pages project.
2. Connect your GitHub repository.
3. Use no build command.
4. Use `/` as the output directory.
5. Deploy.

### Option 3: Hugging Face Static Space

1. Create a new Hugging Face Space.
2. Choose `Static` as the SDK.
3. Upload these files.
4. The page will be hosted as a Hugging Face Space.

## Notes

The chatbot itself continues to run on your existing Gradio Hugging Face Space. This website only embeds it, so you do not need to duplicate the chatbot backend.
