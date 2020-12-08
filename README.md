# livraria

#tutorial
You can create a .github/images directory in your repo and add all your assets there. Assets added here will be available on

https://raw.githubusercontent.com/{github_user_name}/{repo_name}/{branch}/.github/images/{aset_name}.{asset_extension}

Once you push .github/images directory to remote your assets should be available through the mentioned link.
And https://user-images.githubusercontent.com/ is used by GitHub to store images added in issues, PR's, etc.,

You can also create an assets directory in the root of your repo and use a relative path to the image.
/assets/{asset_name}.{asset_extension}

![Alt Text](/assets/{asset_name}.{asset_extension})
With this, images can be previewed without actually pushing to remote.


#referência
https://stackoverflow.com/questions/61537403/how-to-host-image-at-https-user-images-githubusercontent-com-path-filename
