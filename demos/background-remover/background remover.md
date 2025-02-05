# Demo scenario

## Cursor AI - background remover

1. Prepare

- Look at https://fal.ai/models 
  - background remover 
  - api (docs)
- Add doc to cursor

2. Prompt - v0.dev

```
I want a simple application that allows me to upload an image and then send that image to the backend and ultimate show it on the right side of the screen once the result is processed. Also create a simple nav with title and a footer.
```

3. Add to codebase
4. Create app

```
bunx create-next-app .
```

5. Install v0.dev package

```bash
# copy from v0.dev
npx shadcn@latest add ...
```

6. Add ImageUploader to app

```tsx
<div>
  <ImageUploaderComponent />
</div>
```

7. Open composer (shift-command-i)

Select ImageUploader & Page
Prompt

```
I want to wire this up with a fal ai model that removes the background from images, use the image uploader frontend component for the ui and the frontend logic and for the background, lets make a server action that handles the bg removal from fal.
```

FAL_KEY=0c35b913-c2eb-486f-8463-4dcad63d2119:5a336ef762f39ab7f96332f1a0db9fa1


8. Add features

```
I want to add the ability to download the image
I want to have an option to make the image full screen
I want the image to download, not to open in the browser, and add 'x' to close it.
```
