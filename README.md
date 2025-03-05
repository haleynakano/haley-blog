# My Blog

## Getting started
1. Clone this repository.
2. Install [Hugo](https://gohugo.io/getting-started/installing/)
3. When you clone this repository, you need to run the following command:
   ```
   git submodule update --init --recursive
   ```
4. Set up `hugo.yaml` (baseURL, title, and homeInfoParams)

## Create a new post
If you want to create a new post whose title is "My First Post", you can run the following command:
```
hugo new content content/posts/my-first-post
```

- You have to change the command as per your need (e.g., `hugo new content content/posts/any-title-here`).
- You can create a post by editing `content/posts/my-first-post/index.md`. (Write in Markdown.)
- To change the cover image, you can replace `content/posts/my-first-post/cover.png` with your own image.

## Publish the post
By default, the post is not published. If you want to publish the post, you can change the `draft: true` to `draft: false` in `index.md`.

You can change the `date` in `index.md` to the date you want to publish the post.

## Edit the home page
You can edit the home page by editing `hugo.yaml`.
The home info content is in `homeInfoParams` in `hugo.yaml`.

## Run the server
You can run the server by running the following command:
```
hugo server
```

If you want to see the draft posts, you can run the following command:
```
hugo server --buildDrafts 
```
